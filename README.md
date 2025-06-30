# Auto Finance App
A simple and interactive finance dashboard built with **Streamlit** to help you categorize and analyze your bank transaction data.
# Use to Build This Project

1. Programming Language
Python — core language for building the app and data processing.
2. Frameworks & Libraries
Streamlit
For building the interactive web app UI quickly and easily, with minimal frontend code.
Pandas
For reading, manipulating, and processing transaction data in CSV files.
Plotly Express
For creating interactive visualizations (like pie charts) to summarize expenses.
JSON (built-in Python library)
To save and load category-to-keyword mappings persistently.
OS (built-in Python library)
For file system operations, like checking if the categories file exists.
What You Build (Components & Features)

1. File Upload Component
A Streamlit file uploader to allow users to upload their bank transaction CSV files.
2. Data Loader & Parser
Reads uploaded CSV, cleans data (e.g., removing commas in amounts), parses dates, and converts amounts to floats.
3. Automatic Categorization Logic
Categorizes transactions based on keywords associated with each category.
Stores categories and keywords persistently in a JSON file.
4. Category Management UI
Allows users to add new categories dynamically.
Allows editing transaction categories in a table-like data editor.
5. Expense and Payment Tabs
Separates transaction display into two tabs: Expenses (Debits) and Payments (Credits).
6. Summary & Visualization
Shows summary totals by category.
Displays an interactive pie chart of expenses by category.

## Features

- Upload your transaction CSV files.
- Automatically categorize transactions based on customizable keyword lists.
- Add new categories and keywords dynamically.
- Edit and update transaction categories in a spreadsheet-like interface.
- View summarized expense reports by category with interactive pie charts.
- Separate tabs for viewing Expenses (Debits) and Payments (Credits).
- Persistent storage of categories in a JSON file.

## Usage

- Upload a CSV file containing your bank transactions. The CSV should have columns like Date, Details, Amount, and Debit/Credit.
- The app automatically categorizes transactions based on keywords stored in categories.json.
- Add new categories by typing the category name and clicking Add Category.
- Edit transaction categories directly in the table and click Apply Changes to save and update keyword mappings.
- View summaries of expenses and payments in separate tabs, along with visual pie charts for expenses.

## File Format

The CSV file should have at least the following columns:
Column	Description
Date	Transaction date (e.g., 10 Jun 2025)
Details	Transaction details/description
Amount	Transaction amount (numbers only)
Debit/Credit	Whether transaction is Debit or Credit

## Customization

Categories and their associated keywords are stored in categories.json. This file updates automatically as you add new keywords via the app.
Modify or reset this file manually if needed.

## Limitations & Notes

Currently, PDF uploads are accepted in the uploader but not yet supported for parsing.
The categorization matches keywords exactly in the Details column (case-insensitive). Partial matches are not currently supported.
Ensure the CSV format matches the expected column names and date format.

## For Future Improvements Is In Progress

PDF transaction parsing.
More advanced keyword matching (partial and fuzzy matching).
Export categorized transactions and summaries.
User authentication for multi-user support.
