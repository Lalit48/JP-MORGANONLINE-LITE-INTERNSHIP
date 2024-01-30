# JP-MORGANONLINE-LITE-INTERNSHIP

Based on my last knowledge update in January 2022, I don't have any specific information about a program called "JP-MORGANONLINE-LITE-INTERNSHIP." It's possible that this program has been introduced after my last update, or it could be a term or reference that is not widely known.

To obtain accurate and up-to-date information about the "JP-MORGANONLINE-LITE-INTERNSHIP," I suggest visiting the official website of JPMorgan Chase, the company behind the JP Morgan brand. Companies often provide comprehensive details about their internship programs, including application procedures, eligibility requirements, and program specifics on their official websites.

If this is a specific program within JPMorgan Chase, you may also consider reaching out to their human resources or recruitment department for further information. They can offer insights into the structure, objectives, and application process of the internship.

Remember to always rely on official and trustworthy sources when gathering information about internships or any programs, especially when it involves personal or sensitive information.

* TASK 1 (Modify an existing system)

    In firest Task
      Instance Variables:
    
    - cashValue: Represents the monetary value of the reward.
    - milesValue: Represents the value of the reward in miles.
    
    Constructors:
    
    - public RewardValue(double aCashValue): Initializes the object with a specific cash value.
    - public RewardValue(int aMilesValue): Initializes the object with a specific miles value.
    
    Getter Methods:
    
    - public double getCashValue(): Calculates and returns the total cash value, which includes the original cash value plus a conversion of miles to cash using the conversion factor 0.0035.
    - public int getMilesValue(): Calculates and returns the total miles value, which includes the original miles value plus a conversion of cash to miles using the inverse of the conversion factor.

* Task 2 (Unit testing)

    In Secound Task
     Conversion Rate Constant:
    
  - The conversion rate constant is defined as milesToCashConversionRate with a value of 0.0035. This constant is used to convert miles to cash.
    
  Constructors:
    
  - There are two constructors available. One constructor initializes the object with a cash value, while the other constructor initializes it with a miles value.
    
  Getter Methods:
    
   - The getCashValue() method calculates and returns the total cash value, which includes the original cash value plus the conversion of miles to cash. On the other hand, the getMilesValue() method calculates and returns the total miles value, which includes the original miles value plus the conversion of cash to miles.
    
  Test Methods:
    
  - There are two test methods implemented using JUnit's @Test annotations. The first test method, convert_from_cash_to_miles, verifies if the conversion from cash to miles is correct. The second test method, convert_from_miles_to_cash, checks if the conversion from miles to cash is correct.
