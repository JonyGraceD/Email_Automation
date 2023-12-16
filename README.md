## Email Automation using Python

## Overview

This Python project automates the process of sending reminder emails based on data provided in a Google Sheets document.

## Prerequisites

- Python 3.x
- `pandas` library (`pip install pandas`)
- 'dotenv' library ('pip install python-dotenv')

## Setup
1. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Create a Google Sheets document with the required columns: 'invoice_no', 'name', 'email', `due_date`, `reminder_date`, `has_paid`, 'amount', etc.

3. Make the Google Sheets document public, and note the `SHEET_ID` and `SHEET_NAME`.

4. Create files:
    - Create 'main.py' and 'send_email.py' files based on the code provided in the repository
    - Set the `SHEET_ID` and `SHEET_NAME` variables in 'main.py' with Your Google Sheets information.
    - Customize the email content in `send_email.py`.

6. Test the setup:

    ```bash
    python main.py
    ```

## CSV Representation

Here is a representation of the CSV file structure expected by the script:

```csv
invoice_no,name,email,due_date,reminder_date,has_paid,amount
INV-001,John Doe,john@example.com,2023-01-15,2023-01-10,no,100
INV-002,Jane Smith,jane@example.com,2023-02-20,2023-02-15,no,150
# Add more rows as needed
```

---

Feel free to make any additional adjustments based on your project's specifics. If you have any other questions or need further modifications, let me know!
