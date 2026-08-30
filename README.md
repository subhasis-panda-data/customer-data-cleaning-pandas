# Customer Data Cleaning with Python & Pandas

## Project Overview

This project demonstrates a practical data-cleaning workflow using **Python and Pandas** on a customer call-list dataset.

The objective is to identify and resolve common data-quality issues and prepare the dataset for further analysis.

## Objectives

* Identify and remove duplicate records
* Remove unnecessary columns
* Clean inconsistent customer names
* Standardize phone-number formats
* Handle missing and `N/a` values
* Standardize categorical values
* Split address information into separate fields
* Apply business rules to filter records
* Remove records without required contact information
* Reset the dataframe index

## Data Cleaning Workflow

The project follows these main steps:

1. Load the Excel dataset using Pandas
2. Inspect the dataset structure and values
3. Identify and remove duplicate records
4. Remove unnecessary columns
5. Clean customer name values
6. Standardize phone-number values
7. Handle missing and `N/a` values
8. Standardize `Yes/No` and `Y/N` values
9. Split the address field into structured columns
10. Remove records marked as `Do_Not_Contact`
11. Remove records without phone numbers
12. Reset the dataframe index
13. Perform final data-quality checks

## Tools & Technologies

* **Python**
* **Pandas**
* **Jupyter Notebook**
* **Excel**

## Key Pandas Operations

The project demonstrates practical use of:

```text
read_excel()
head()
info()
drop_duplicates()
drop()
str.strip()
str.replace()
str.split()
replace()
fillna()
isna()
value_counts()
reset_index()
```

## Key Data Cleaning Tasks

### Duplicate Removal

Duplicate customer records are identified and removed to prevent duplicate information from affecting downstream analysis.

### Text Cleaning

Inconsistent characters and formatting in customer name fields are cleaned using Pandas string operations.

### Phone Number Standardization

Phone numbers containing different separators and formats are standardized into a consistent numeric representation.

### Missing Value Handling

`N/a` and missing values are identified and handled using Pandas missing-value operations.

### Address Transformation

The original address field is separated into structured fields such as:

* Street Address
* State
* ZIP Code

### Categorical Standardization

Customer-related fields containing variations such as `Yes`, `No`, `Y`, and `N` are standardized for consistency.

### Business Rule Filtering

Records marked as `Do_Not_Contact = Y` are removed, along with records that do not contain a phone number.

## Project Structure

```text
customer-data-cleaning-pandas/
│
├── Customer_Data_Cleaning_Pandas.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

> If a sample Excel dataset is included, it should contain only safe/non-sensitive data.

## Learning Outcomes

This project strengthened practical understanding of:

* Data preprocessing
* Data quality assessment
* Pandas data manipulation
* String transformation
* Missing-value handling
* Duplicate detection
* Conditional filtering
* Data standardization
* Preparing datasets for downstream analysis

## Conclusion

Data cleaning is an important first step in any analytics workflow. This project demonstrates how Python and Pandas can be used to transform an inconsistent customer dataset into a cleaner and more structured format suitable for further analysis and reporting.

## Author

**Subhasis Panda**

Aspiring Data Analyst | Python | SQL | Power BI | Statistics | Machine Learning
