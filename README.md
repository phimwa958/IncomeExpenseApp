# IncomeExpenseApp

## Overview
The **IncomeExpenseApp** is a simple income and expense tracking application built using Python and the wxPython library. It provides a graphical user interface (GUI) to input, categorize, and view financial transactions. The application stores data in an Excel file for easy access and modification.

## Features
- Add income and expense entries with descriptions, amounts, and notes.
- View all transactions in a detailed list with columns for date, description, amount, type, and notes.
- Automatically calculate and display the total balance.
- Persist data in an Excel file (`income_expense_data.xlsx`)

## Requirements
### Python Libraries
- `wxPython`
- `openpyxl`
- `datetime`
- `os`

Install required libraries using pip:
```bash
pip install wxpython openpyxl
```

## How to Run
1. Clone or download the repository.
2. Ensure all required Python libraries are installed.
3. Run the `IncomeExpenseApp` script:
   ```bash
   python income_expense_app.py
   ```

## User Guide
### Adding Transactions
1. Enter a description in the "Description" field.
2. Input the amount in the "Amount" field.
3. Optionally, add notes in the "Notes" field.
4. Click "Add Income" or "Add Expense" to save the transaction.

### Viewing Transactions
- All transactions are displayed in the list with sortable columns for Date, Description, Amount, Type, and Notes.
- The total balance is updated dynamically.

## File Structure
- **income_expense_app.py**: Main application script.
- **income_expense_data.xlsx**: Data file for storing transaction records.

## Example
1. Start the application.
2. Add an income entry:
   - Description: "Salary"
   - Amount: 1000
   - Notes: "September salary"
3. Add an expense entry:
   - Description: "Groceries"
   - Amount: 200
   - Notes: "Weekly shopping"
4. View the updated total balance and all transactions in the list.

## Contributing
1. Fork the repository.
2. Create a new feature branch.
3. Submit a pull request for review.

## License
This project is open-source and available under the [MIT License](LICENSE).

