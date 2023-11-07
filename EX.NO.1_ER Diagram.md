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
### Relational model
![Screenshot 2023-11-07 152052](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/187c6f3f-276e-41c0-8c4d-8acfe4bcabdc)


### SQL DDL Schema 
![Screenshot 2023-11-07 152124](https://github.com/LATHIKESHWARAN/DBMS/assets/119393556/c8d92d2e-db32-4488-9364-7fa3e96b9955)

## RESULT 
<div align="justify">
Thus the ER diagram was drawn and relational diagram, SQL DDL staements are generated using ERD plus tool.
</div>
