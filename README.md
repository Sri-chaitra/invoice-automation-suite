# Invoice Automation Suite

An end-to-end Python-based solution to automate the process of extracting invoice data from emails and managing it through a desktop application built with Tkinter.

## 🧾 Overview

This suite integrates email reading, PDF invoice extraction, validation, and a user-friendly UI to track and manage invoice records—all in one workflow.

## 🚀 Features

- ✅ Automatically read emails and download invoice PDFs
- ✅ Extract relevant fields (Order ID, Order Date, Invoice Date)
- ✅ Validate duplicate entries and check for missing fields
- ✅ Tkinter-based UI for manual uploads, tracking, and viewing
- ✅ Optional Excel export for reporting
- ✅ Clean and modular Python code for each task

## 🛠 Tech Stack

- **Language**: Python 3
- **Email Handling**: `imaplib`, `email`, `os`
- **PDF Processing**: `pdfplumber` / `PyPDF2`
- **GUI**: `Tkinter`
- **Data Management**: `pandas`, `openpyxl` (for Excel export)

## 📂 Project Structure

invoice-automation-suite/
├── email_reader.py  # Connects to inbox, downloads invoice PDFs
├── pdf_extractor.py  # Extracts order info from PDFs
├── validator.py  # Validates duplicates and required fields
├── ui.py # Tkinter-based GUI for invoice tracking
├── utils.py # Helper functions
├── data/ # Folder for storing PDFs or Excel logs
├── requirements.txt # Python dependencies
└── README.md



## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/invoice-automation-suite.git
   cd invoice-automation-suite
   
2. Install required packages
   pip install -r requirements.txt
   
3. Run the full workflow
 Start by reading emails and extracting data:
   python email_reader.py
 Then launch the Tkinter UI:
   python ui.py
