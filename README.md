# Beta Bank Customer Retention Model

## The Problem
Beta Bank customers are leaving little by little each month. The bank determined it's cheaper to save existing customers than to attract new ones. Knowing which customers will leave soon would be a valuable tool to help Beta Bank target the right customers before they decide to leave.

## Prediction Model
Beta Bank hopes a sufficent prediction model can be made. It's sufficiency depends if a an F1 score of at least 0.59 is attained. The AUR-ROC metric will also be compared. Client behaviour including whether they have terminated their contract or not has been provided. A description of data follows.

## Data Description

`RowNumber` — data string index

`CustomerId` — unique customer identifier

`Surname` — surname

`CreditScore` — credit score

`Geography` — country of residence

`Gender` — gender

`Age` — age

`Tenure` — period of maturation for a customer’s fixed deposit (years)

`Balance` — account balance

`NumOfProducts` — number of banking products used by the customer

`HasCrCard` — customer has a credit card

`IsActiveMember` — customer’s activeness

`EstimatedSalary` — estimated salary

`Exited` — сustomer has left (if 1)

## The Process
The process will follow these four steps:

- Prepare the data
- Examine the balance of classes
- Improve model quality
- Perform final testing
