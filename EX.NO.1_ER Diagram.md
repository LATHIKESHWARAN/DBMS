# EXP NO 1: ER DIAGRAM CREATION, RELATIONAL MODEL AND SCHEMA GENERATION  
### DATE
## AIM:
<div align="justify">
   To create a ER Diagram for Bank management system or College management system using ERD Plus tool and generate the relational model with schema. 
</div>

## Algorithm
1. Create a login with https://erdplus.com.
2. Create a new ER Diagram with name
3. Create a strong entity, relation and attributes.
4. Create a weak entity, relation and attributes.
5. Specify attributes unique, multivalued and composite attributes.

### ER Diagram 
![image](https://github.com/DrUmaRaniV/DBMS/assets/119393556/86a857f2-ab26-4cd0-b962-f67dd81ba1d2)


### Relational model
![image](https://github.com/DrUmaRaniV/DBMS/assets/119393556/650a6746-dee7-46f9-bdb0-435d96ffedfb)


### SQL DDL Schema 
```
CREATE TABLE BANK
(
  code INT NOT NULL,
  Name INT NOT NULL,
  Addr INT NOT NULL,
  PRIMARY KEY (code)
);

CREATE TABLE BANK_BRANCH
(
  Addr INT NOT NULL,
  Branch_no INT NOT NULL,
  PRIMARY KEY (Branch_no)
);

CREATE TABLE Loan
(
  Loan_no INT NOT NULL,
  Amount INT NOT NULL,
  Type INT NOT NULL,
  PRIMARY KEY (Loan_no)
);

CREATE TABLE Account
(
  Acct_no INT NOT NULL,
  Balance INT NOT NULL,
  Type INT NOT NULL
);

CREATE TABLE CUSTOMER
(
  Name INT NOT NULL,
  Ssn INT NOT NULL,
  Addr INT NOT NULL,
  Phone INT NOT NULL,
  PRIMARY KEY (Ssn)
);
```
## RESULT 
<div align="justify">
Thus the ER diagram was drawn and relational diagram, SQL DDL staements are generated using ERD plus tool.
</div>
