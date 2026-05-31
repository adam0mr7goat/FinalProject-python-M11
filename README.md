# FinalProject-python-M11
# Course Registration System 🎓

A Python-based system that manages candidate registrations for a course. Built as a final project for the TGPSI program at Escola Secundária D. Pedro V.

## What it does
- Register new candidates with their full info
- Automatically evaluates if they are accepted or rejected based on age and education level
- Lists all registered candidates
- Search for a candidate by name
- Exports accepted and rejected candidates to separate JSON files
- Generates a PDF receipt for each candidate after registration
- Sends an automatic email to the candidate with their registration result

## How to run
1. Clone the repo
2. Install the required libraries:
```
pip3 install fpdf2
pip3 install secure-smtplib
```
3. Add your Gmail and app password in the `send_email()` function
4. Run the file:
```
python3 projetoFinal-main.py
```

## Technologies used
- Python 3
- JSON for data storage
- fpdf2 for PDF generation
- smtplib for email sending

## Author
Adam Ibrahim — 11º 14, TGPSI
Escola Secundária D. Pedro V
