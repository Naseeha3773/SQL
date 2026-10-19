**DATABASE SCHEMA**
**patients**
patient_id- INTEGER PK
first_name- VARCHAR(30)
last_name- VARCHAR(30)
gender- CHAR(1)
birth_date- DATE
city- VARCHAR(30)
province_id- CHAR(2)
allergies- VARCHAR(80)
height- DECIMAL(3,0)
weight- DECIMAL(4,0)


**doctors**
doctor_id- INTEGER PK
first_name- VARCHAR(30)
last_name- VARCHAR(30)
specialty- VARCHAR(25)


**admissions**
admission_id- INTEGER PK
patient_id- INT
admission_date- DATE
discharge_date- DATE
diagnosis- VARCHAR(50)
attending_doctor_id- INT
admission_cost- DECIMAL(10,2)
