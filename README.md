# sales-analytics-system


## Project Overview
The **Sales Analytics System** is a Python-based notebook project designed to analyze sales transactions, validate data, apply filters, enrich sales records with product information, and generate comprehensive reports. The system is robust, handles missing or invalid data gracefully, and provides clear console output for all steps of the workflow.

Key features include:

- Reading and parsing sales data from a text file.
- Cleaning and validating transactions.
- Displaying filter options based on regions and transaction amounts.
- Performing sales analysis and enrichment using product information.
- Saving enriched data and generating reports.

---

## Folder Structure

  sales-analytics-system/
├── README.md
├── main.ipynb
├── utils/
│ ├── file_handler.ipynb # Functions to read/write data files
│ ├── data_processor.ipynb # Functions for parsing, cleaning, and validating data
│ ├── api_handler.ipynb # Functions to fetch product information (if API available)
│ └── report_generator.ipynb # Functions to generate sales reports
├── data/
│ └── sales_data.txt # Provided sales transactions
├── output/
│ └── sales_report.txt # Generated report from analysis


## Environment

Python 3.x

---

## How to Run

1. Open `main.ipynb` in Jupyter Notebook or VS Code.
2. Ensure that the `data/sales_data.txt` file exists.
3. Run all cells sequentially.
4. Follow prompts in the console:
   - Choose whether to filter data by region or amount.
5. The system will:
   - Parse and clean transactions.
   - Display filter options.
   - Validate data.
   - Perform analysis and enrichment.
   - Save enriched data to `data/enriched_sales_data.txt`.
   - Generate a report in `output/sales_report.txt`.
6. Check the `output/` folder for the generated report and enriched data.

---

## Features

- **Data Validation:** Automatically identifies and removes invalid transactions.
- **Filtering:** Allows filtering transactions based on regions and transaction amount ranges.
- **Enrichment:** Integrates product information into sales data.
- **Analysis:** Computes and summarizes sales metrics.
- **Reporting:** Generates human-readable sales reports using modular functions.

---

## Notes

- All helper functions are modular and stored in the `utils/` folder for easy maintenance.
- The system handles missing or invalid data gracefully and prints user-friendly messages.
- API calls are optional; if no product mapping is available, enrichment still proceeds safely.
- Ensure your Python environment supports running Jupyter notebooks.

---

## Author

Developed by Heena Kumari as part of the Sales Analytics project.
