# 💳 Bank Statement Analyzer

A Python project that automates the consolidation and standardization of bank statements from multiple financial institutions.

The application imports CSV bank statements, cleans and standardizes the data using **Pandas**, classifies transactions as **Income** or **Expense**, and exports the final dataset to a formatted Excel spreadsheet using **OpenPyXL**.

---

## 🚀 Features

- Import bank statements from multiple banks
- Clean and standardize data
- Merge multiple CSV files into a single dataset
- Classify transactions as Income or Expense
- Export a formatted Excel report

---

## 🛠️ Technologies

- Python
- Pandas
- OpenPyXL

---

## 📁 Project Structure

```text
Bank-Statement-Analyzer/
│
├── data/
│   ├── inter.csv
│   ├── nubank.csv
│   └── santander.csv
│
├── output/
│   └── excel_extrato.xlsx
│
├── main.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Bank-Statement-Analyzer.git
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the project:

```bash
python main.py
```

The project will generate a standardized and formatted Excel report containing all processed bank statements.

---

## 📊 Workflow

```text
CSV Bank Statements
        │
        ▼
Data Cleaning (Pandas)
        │
        ▼
Data Standardization
        │
        ▼
Transaction Classification
        │
        ▼
Excel Report (OpenPyXL)
```

---

## 🎯 Skills Demonstrated

- Data Cleaning
- Data Transformation
- ETL
- CSV Processing
- Excel Automation
- Python Programming

---

## 📄 License

This project is licensed under the MIT License.
