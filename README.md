💰 Auto Finance App

A simple and interactive finance dashboard built with Streamlit & Pandas to help you categorize and analyze your 💳 bank transaction data.

🛠️ Use to Build This Project

1. 🐍 Programming Language
Python — core language for building the app and handling data.
2. 🧰 Frameworks & Libraries
Streamlit
🚀 For building the interactive web app UI quickly and easily, with minimal frontend code.
3. Pandas
📊 For reading, manipulating, and processing transaction data in CSV files.
4. Plotly Express
🥧 For creating interactive visualizations (like pie charts) to summarize expenses.
JSON (built-in)
🗃️ To save and load category-to-keyword mappings persistently.
5. OS (built-in)
📁 For file system operations like checking if the categories file exists.
🧱 What You Build (Components & Features)

📤 File Upload Component
A Streamlit file uploader to upload your bank transaction CSV files.
🧹 Data Loader & Parser
Cleans and processes data — removes commas, parses dates, converts amounts.
🧠 Automatic Categorization Logic
Assigns categories to transactions using keyword matching stored in categories.json.
🧮 Category Management UI
Add new categories, edit existing ones using a spreadsheet-style interface.
🧾 Expense and Payment Tabs
Separate views for Debits (Expenses) and Credits (Payments).
📊 Summary & Visualization
View total expenses per category and an interactive pie chart.
✨ Features

📂 Upload your transaction CSV files.
🤖 Automatically categorize transactions with keyword logic.
📝 Add new categories and keywords on the fly.
🧾 Edit and update categories in an interactive table.
📊 See summary reports and visual charts.
🔀 Switch between Expenses and Payments tabs.
💾 Persistent category data stored in categories.json.
🧪 Usage

Upload a CSV file with these columns: Date, Details, Amount, and Debit/Credit.
Transactions are categorized automatically based on keywords.
Add a new category with the text input + "Add Category" button.
Use the editor to change a category and click "Apply Changes".
View expenses in pie charts and payment totals in a clean layout.
🧾 File Format

Your CSV file should have the following columns:

📅 Column	📝 Description
Date	Transaction date (e.g., 10 Jun 2025)
Details	Description/details of the transaction
Amount	Amount (e.g., 2500)
Debit/Credit	Specify if it’s a Debit or Credit
⚙️ Customization

🔧 All category data is saved in categories.json.
✍️ You can modify or reset it manually if needed.
✅ Auto-updates when you categorize a new transaction.
⚠️ Limitations & Notes

📄 PDF uploads are accepted but not yet parsed (coming soon).
🔍 Keyword match is exact (not partial/fuzzy) on Details field.
📋 Ensure your CSV matches the required format and column names.
🚧 Future Improvements (In Progress)

📑 PDF transaction parsing.
🔎 Smarter keyword matching (partial/fuzzy logic).
📥 Export categorized data and summary reports.
👤 User login & multi-user dashboard support.
