# Car Data ETL Pipeline

A lightweight Python ETL pipeline that extracts car data from CSV, JSON, and XML files, transforms it for consistency, and loads it into a unified CSV output with logging support.

## 🚗 Project Overview

This project implements a basic ETL (Extract, Transform, Load) pipeline using Python. It reads car data from different file formats (CSV, JSON, XML), standardizes the data (e.g., formatting, rounding, capitalization), and writes the cleaned dataset to a target CSV file. All actions are logged with timestamps for traceability.

## 📂 Directory Structure

```
.
├── etl_pipeline.py
├── log_file.txt
├── transformed_car_data.csv
├── data/
│   ├── cars.csv
│   ├── cars.json
│   └── cars.xml
```

> 📌 Note: Ensure your data files are placed in the same directory as `etl_pipeline.py` or adjust the script as needed.

## 🛠 Requirements

- Python 3.6 or higher
- pandas

Install required packages:

```bash
pip install pandas
```

## 🚀 How to Run

1. Clone the repository and navigate into it:

```bash
git clone https://github.com/your-username/car-data-etl-pipeline.git
cd car-data-etl-pipeline
```

2. Add your CSV, JSON, and XML files into the project directory.

3. Run the ETL pipeline:

```bash
python etl_pipeline.py
```

4. Output:
   - Cleaned data is saved to `transformed_car_data.csv`
   - A log of the ETL steps is written to `log_file.txt`

## 🧪 Sample Log Output

```
2025-Apr-29-13:01:02,ETL Job Started
2025-Apr-29-13:01:02,Extract phase Started
2025-Apr-29-13:01:03,Extract phase Ended
2025-Apr-29-13:01:03,Transform phase Started
2025-Apr-29-13:01:03,Transform phase Ended
2025-Apr-29-13:01:04,Load phase Started
2025-Apr-29-13:01:04,Load phase Ended
2025-Apr-29-13:01:04,ETL Job Ended
```

## ✍️ Author

Developed by [Your Name]

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.