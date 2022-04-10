# Loan Qualifier Application
This is a CLI (Command Line Interface) application that determines a User's qualifications for a loan.  It asks questions of the user related to loan criteria.  Based on User's inputs, the system decides which loans this User will qualify for.  The system then provides the option to save the qualified loans as a csv file for the User to import as an Excel document. 

---

## Technologies
python 3.9.10
questionary 
fire

---

## Installation Guide

Download the application and all files within folder "LOAN_QUALIFER_APP"
Navigate to the root of the folder "LOAN_QUALIFER_APP"
Run the application by opening up your Terminal or Console App and typing the command: 'python app.py'

---

## Usage

Loan Qualified app asks questions of the User:
- Provide file path location of the file data/daily_rate_sheet.csv
- Answer questions as :
? Enter a file path to a rate-sheet (.csv): /Users/abhi/Documents/GitHub/loan_qualifier_app/data/daily_rate_sheet.csv
? What's your credit score? 700
? What's your current amount of monthly debt? 1000
? What's your total monthly income? 3000
? What's your desired loan amount? 3000
? What's your home value? 100000
The monthly debt to income ratio is 0.33
The loan to value ratio is 0.03.
Found 11 qualifying loans
? Would you like to save the qualifying loans as a csv file? Yes
? Enter a file path where you would like to save the qualifying loans (.csv): /Users/abhi/Documents/GitHub/loan_qualifier_app/data/qualifying_loans.c
sv

---

## Contributors

Abhi Banerjee

---

## License

Gnu Public License
