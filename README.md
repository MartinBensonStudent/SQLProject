This project was used to design and implement a database that could be deployed in a commercial database management system using Codd's Rules. 
This was built using a relational database and the premise/narrative was to design something that could be used in a dental practice.

Some examples of queries you could use within this project are included below:

SELECT
SELECT * FROM PATIENT WHERE OUTSTANDING_BALANCE > 100.00;

INSERT
INSERT INTO PATIENT (PATIENT_NAME, PHONE, OUTSTANDING_BALANCE, ADDRESS, LAST_VISIT_DATE, DOB, EMAIL, 
PATIENT_REFERENCE_NUMBER) VALUES ('Greg Miller', '0892345678', 0.00, '64 Zoo Lane Ennis Co.Clare', '25-APRIL-22', 
'09-OCTOBER-69', 'GREGMILLER@GMAIL.COM', 15);

Update
UPDATE PATIENT SET OUTSTANDING_BALANCE=333.33 WHERE PATIENT_REFERENCE_NUMBER=15;

Delete
DELETE FROM PATIENT WHERE PATIENT_REFERENCE_NUMBER=15;
