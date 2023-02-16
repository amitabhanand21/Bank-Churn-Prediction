 Aim of this code is to find the most accurate and precise model to predict, which clients (test data) will stay and which are hesitant and might plan to leave the company.
 
 Dataset has following attributes:

    Rownumber: Unique ID for every row
    CustomerID: Unique ID for every client
    Surname: Client's surname
    CreditScore: Client's credit score
    Geography: Country of client's origin
    Gender: Client's gender
    Age: Client's age
    Tenure: Number of years for which the client has been with the bank
    Balance: Client's balance on account
    NumOfProducts: Number of client's products
    HasCrCard: Flag whether client has credit card or not
    IsActiveMember: Flag whether client is active member of bank or not
    EstimatedSalary: Client's annual estimated salary in euros
    Exited: Target variable, flag, whether client left the bank or not



Had to use random over sampler since target variable was highly non-homogeneous.
