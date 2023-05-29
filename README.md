# Loan Qualifier App

User Story:
As a user, I need the ability to save the qualifying loans to a CSV file so that I can share the results as a spreadsheet.

- When the user runs the loan qualifier CLI application, the tool prompts the user to save the results as a CSV file to a specified file path.

- Given that I’m using the loan qualifier CLI, when I run the qualifier, then the tool should prompt the user to save the results as a CSV file.
- Given that no qualifying loans exist, when prompting a user to save a file, then the program should notify the user and exit.
- Given that I have a list of qualifying loans, when I’m prompted to save the results, then I should be able to opt out of saving the file.
- Given that I have a list of qualifying loans, when I choose to save the loans, the tool should prompt for a file path to save the file.
- Given that I’m using the loan qualifier CLI, when I choose to save the loans, then the tool should save the results as a CSV file.

---

## Technologies

Describe the technologies required to use your project such as programming languages, libraries, frameworks, and operating systems. Be sure to include the specific versions of any critical dependencies that you have used in the stable version of your project.

Python 3.7 - 3.9
fire
questionary

---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.

Clone the repo.
Navigate to local directory.
Run python app.py in terminal or command prompt.

---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

% python app.py
Enter a file path to a rate-sheet (.csv): data/daily_rate_sheet.csv
? What's your credit score? 800
? What's your current amount of monthly debt? 1000
? What's your total monthly income? 10000
? What's your desired loan amount? 500000
? What's your home value? 650000
The monthly debt to income ratio is 0.10
The loan to value ratio is 0.77.
Found 5 qualifying loans
? Do you want to save your qualifying loans as CSV? Yes
? What's the path and filename to save the CSV file? qualifier/output.csv
CSV saved successfully!


---

## Contributors

https://github.com/fonzeon

---

## License

MIT License
