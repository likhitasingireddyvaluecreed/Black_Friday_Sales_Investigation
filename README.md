
# Black Friday Sales and Inventory Investigation

A data engineering project built using PySpark and Spark SQL to process and analyze Black Friday sales and inventory data.

## Tech Stack
- Python
- Apache PySpark
- Spark SQL
- Jupyter Notebook
- Parquet

## Repository Structure

```text
Black-Friday-Sales/
│
├── black_friday_sales.ipynb
├── data/
│   └── raw/
│       ├── customers.csv
│       ├── products.csv
│       ├── orders.csv
│       └── inventory_events.csv
│
└── output/
```

## Prerequisites
- Python 3.x
- Java (required for PySpark)
- Jupyter Notebook

## Setup and Installation

**1. Clone the repository**
```bash
git clone <repository-url>
cd <repository-folder>
```

**2. Create and activate a virtual environment**
```bash
python -m venv venv
```

Windows:
```bash
venv\Scripts\activate
```

**3. Install dependencies**
```bash
pip install pyspark jupyter pandas
```

## Dataset Setup

Place the four required CSV files inside `data/raw/`:

- `customers.csv`
- `products.csv`
- `orders.csv`
- `inventory_events.csv`

## Run the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `black_friday_sales.ipynb` and execute the cells sequentially.

Generated Parquet files and other project outputs are stored in the `output/` directory.

## Author

**[Your Name]**  
B.Tech – Computer Science and Engineering