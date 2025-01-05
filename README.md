# Excel to PDF Invoice Project

This project processes Excel invoice files and converts them into PDF invoices, which are then saved in a designated folder. The project uses Python libraries such as pandas, glob, and FPDF to perform file reading, data manipulation, and PDF generation.

### Features

Automatic File Detection: Locates all Excel files in a specified folder (invoices).

Data Extraction: Reads and extracts data from each file using pandas.

Dynamic PDF Creation: Generates well-formatted PDFs with invoice details and a product table.

Customizable Design: Includes invoice number, date, company name, and an optional logo.

Summary Table: Adds a total price at the end of each invoice.

### Workflow Overview

Import Required Libraries: Ensure pandas, FPDF, and pathlib are installed.

Locate Excel Files: Use glob to find all .xlsx files in the invoices folder.

Process Each File:

Read data using pandas.

Extract invoice number and date from the filename.

Create a formatted PDF with the data.

Generate PDFs: Save the generated PDF invoices into the PDFs folder.
