### Google Drive
[Link](https://drive.google.com/drive/folders/1nPUPdYoVNr7OATSSF4GrCffHZkUWab2Y?usp=sharing)

### Cleaned columns
- Outliners removed (lmk if u want to remove more)
- All numbers in <b>int</b> unless specified

1. <b>GGGrade :</b> Grant Group Grade (1 - 7)</br>  
1. <b>Validation :</b> Validation status of the borrower 
    - 0: Not verified
    - 1: Source verified
    - 2: Fully verified
1. <b>Yearly Income (in USD) :</b> Total yearly income of the borrower 
1. <b>Home Status :</b> Borrower living status  
    - Types: "mortgage" (0), "rent" (1), "own" (2), "other" (3), "none" (4)
1. <b>Lend Amount :</b> Total funded amount to borrower
1. <b>Deprecatory Records:</b> An entry that may be considered negative by lenders because it indicates risk and
hurts your ability to qualify for credit or other services
1. <b>Interest Charged (in USD) :</b> Interest charged on total amount
    - 2dp numbers
1. <b>Inquiries :</b> Number of inquiries over the last 6 Months (0 - 8)
1. <b>Present Balance (in USD) :</b> Current balance in the borrower account
1. <b>Gross Collection :</b> The gross amount payable by way of Settlement or judgment in respect of the Claims, excluding any costs (0 - 26308; 98% is 0)
1. <b>Sub GGGrade :</b> Sub Grant Group Grade (11 - 45)
1. <b>State :</b> State to which borrower belong
    - categorical data of 0 - 50 sorted according to [the full name of the states](https://state.1keydata.com/state-abbreviations.php), and 50 as DC (Washington DC)
1. <b>Duration (in years) :</b> Duration for the amount is funded to borrower
    - Either 3 or 5 
1. <b>Unpaid Amount (in USD) :</b> Unpaid balance on the credit card 
1. <b>Reason :</b> Reason for loan application
    - Reasons: "car" (0), "credit_card" (1), "debt_consolidation" (2), "home_improvement" (3), "house" (4), "major_purchase" (5), "medical" (6), "moving" (7), "rentwable_energy" (8), "small_business" (9), "vacation" (10), "wedding" (11), "other" (12)
1. <b>Due Fee :</b> Charges incurred if the payment on loan amount is delayed (0.00 - 169.05; 99% is 0)
1. <b>Default :</b> Target variable (Prediction of whether or not it will default)