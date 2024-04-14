# taxcalculation
[TEST CASES]
 (1.)  GrossIncome=700000
       ExtraIncome=50000
       Deduction=50000
       Age=30
    OUTPUT=>NetIncome=700000
            no tax applied
            overallIncome=700000
(2.)  GrossIncome=100000
       ExtraIncome=60000
       Deduction=60000
       Age=50
    OUTPUT=>NetIncome=1000000
             tax appliedon this amount=80000
             overallIncome=9200
(3.)  GrossIncome=1000000
       ExtraIncome=70000
       Deduction=70000
       Age=35
    OUTPUT=>NetIncome=1000000
             tax applied on this amount=60000
             overallIncome= 940000 
(4.)  GrossIncome=1000000
       ExtraIncome=80000
       Deduction=80000
       Age=75
    OUTPUT=>NetIncome=1000000
             tax applied on this amount=20000
             overallIncome=980000
