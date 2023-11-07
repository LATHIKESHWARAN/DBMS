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
![Screenshot 2023-11-07 152052](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/ba49c2f9-ce9f-4c52-9e38-01ed5b4f0797)


### Relational model
![Screenshot 2023-11-07 152124](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/ac1ef09e-b510-41ac-85ff-3faaa3777ebb)


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
