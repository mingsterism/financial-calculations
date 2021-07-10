## App structure
Financial Profile for each year of their life
1. Income
2. Expenses
3. Assets
4. Liabilities

**Primary Income Milestones** <br>
Able to set checkpoints for primary income earned throughout the years
eg: 
- Age 24: RM2000
- Age 34: RM8000
- Age 45: RM15000
- Age 55: RM20000



**Function Calculations** <br>
A proposed structure for all functions below is to generate an array of numbers, which is every year. This can be added to a DataTable for computation. Example: a user takes a loan for a car for a duration of 10 years. Thus, the function should generate the repayment schedule for the car every year for the next 10 years and return an array of numbers.
1. LoanRepaymentsProjection
   1. project the loan repayments throughout the duration of the loan
   2. Loans can be anything that requires the individual to borrow money
2. AssetAppreciationProjection
   1. Project the appreciation of the asset
      1. savings
      2. investments
      3. property
3. AssetDepreciationProjection
   1. Certain assets depreciation instead of appreciate
      1. car
      2. equipment
4. IncomeProjection
   1. income projected between two different checkpoints and grows linearly. EG: from age 24 to 34, income is growing at a linear rate until it reaches the salary at age 34.
5. ExpensesProjection
   1. Personal Expenses
      1. individual maps out all their expenses and it remains constant throughout each year unless changed
   2. Family Expenses
      1. remains constant throughout the years unless changed