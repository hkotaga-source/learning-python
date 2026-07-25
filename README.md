# Learning Python — Pandas DataFrame Example

A beginner-friendly example that creates a simple pandas DataFrame and prints it.

## What this does

Creates a table of people with Name, Age, Salary, and City, then displays it using pandas.

## Requirements

- Python 3.8+
- pandas

## Setup

```bash
# Create and activate a virtual environment (recommended)
python3 -m venv .venv
source .venv/bin/activate   # Linux/macOS
# .venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt
```

## Run

```bash
python dataframe_example.py
```

## Expected output

```
--- First DataFrame ---
      Name  Age  Salary     City
0    Alice   25   50000      NYC
1      Bob   30   60000       LA
2  Charlie   35   70000      NYC
3    Diana   40   80000  Chicago
```

## Project structure

```
learning-python/
├── dataframe_example.py   # Main script
├── requirements.txt       # Dependencies
├── .gitignore
└── README.md
```
