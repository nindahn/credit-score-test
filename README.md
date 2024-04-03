# credit-score-test
2022

## application_record.csv		
ID:	Client number <br />
CODE_GENDER:	Gender <br />
FLAG_OWN_CAR:	Is there a car	<br />
FLAG_OWN_REALTY: Is there a property <br />
CNT_CHILDREN:	Number of children <br />
AMT_INCOME_TOTAL: Annual income <br />
NAME_INCOME_TYPE: Income category <br />	
NAME_EDUCATION_TYPE:	Education level	<br />
NAME_FAMILY_STATUS: Marital status <br />	
NAME_HOUSING_TYPE:	Way of living	<br />
DAYS_BIRTH:	Count backwards from current day (0), -1 means yesterday <br />
DAYS_EMPLOYED:	Start date of employment (Count backwards from current day (0). If positive, it means the person currently unemployed) <br />
FLAG_MOBIL:	Is there a mobile phone	<br />
FLAG_WORK_PHONE:	Is there a work phone	<br />
FLAG_PHONE:	Is there a phone <br />
FLAG_EMAIL:	Is there an email <br />	
OCCUPATION_TYPE:	Occupation <br />	
CNT_FAM_MEMBERS:	Family size <br />	

## credit_record.csv		
ID:	Client number	<br />
MONTHS_BALANCE:	The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on <br />
STATUS:	0: 1-29 days past due <br />
        1: 30-59 days past due <br />
        2: 60-89 days overdue <br />
        3: 90-119 days overdue <br />
        4: 120-149 days overdue <br />
        5: Overdue or bad debts, write-offs for more than 150 days <br />
        C: paid off that month <br />
        X: No loan for the month <br />
