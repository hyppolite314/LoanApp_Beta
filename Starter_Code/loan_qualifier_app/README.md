# Loan Qualifier App

This app is designed to increase automation of the loan application process. This saves time for both the client (borrower) as well as the lenders in
throughout the real estate industry. Effectively, this is a command line application to match applicants with qualifying loans.

---

## Technologies

Required programs, systems, and overall dependencies:

Python (version 3.0 or later)
Fire
Pathlib
tkinter
sys
questionary

---

## Installation Guide

`pip install Fire`
`pip install Pathlib`

---

## Usage

Prompting the User for file path:

```python
def save_qualifying_loans(qualifying_loans):
    save_to_file = questionary.text("Would you like to save qualifying loans to a CSV?(yes/no)").ask()
    save_to_file = (save_to_file)

    if save_to_file == "yes":
        csvpath = questionary.text("Enter a file path for qualifying loans (.csv):").ask()
        csvpath = Path(csvpath)
```

![Screenshot of Terminal](https://github.com/hyppolite314/LoanApp_Beta/blob/main/terminal_scrnshot.png?raw=true)

---

## Contributors

Reginald Hyppolite
https://www.linkedin.com/in/reginald-hyppolite-nyc/

Shout out to all the great TAs and Professor V

---

## License

N/A -- Free open.ware