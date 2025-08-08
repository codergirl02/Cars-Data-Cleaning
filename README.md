# 🧼 Used Car Data Cleaning Project

This project focuses on cleaning and preparing a used car dataset for further analysis. The dataset includes features like car name, variant, transmission, kilometers driven, ownership type, fuel type, registration location, price, and date.

## 📌 Objective

The goal is to practice data cleaning skills using Python in a Jupyter Notebook by:
- Removing unwanted characters from price and km driven columns
- Converting date formats
- Fixing encoding issues (e.g., ₹ symbol)
- Handling missing or inconsistent values
- Changing data types where required

## 🛠️ Tools Used

- Python (pandas)
- Jupyter Notebook

## 📁 Dataset Overview

| car_name           | variant      | transmission | km_driven | owner_type | fuel_type | registration | price     | date       |
|--------------------|--------------|--------------|-----------|-------------|------------|---------------|------------|------------|
| 2018 Tata NEXON     | XM 1.2       | Manual       | 95,230 km | 1st Owner   | Petrol     | UP-16         | ₹6,50,000 | 31-Dec-18  |
| 2017 Renault Kwid   | 1.0 RXT Opt  | Manual       | 72,956 km | 2nd Owner   | Petrol     | HR-11         | ₹3,19,000 | 05-Mar-19  |

## 📈 Key Cleaning Steps

- Removed “km” and commas from `km_driven`, converted to numeric
- Cleaned `price` by removing currency symbols and commas
- Fixed encoding issues (e.g., “â‚¹” → “₹”)
- Converted `Date` column to datetime format
- Seperated year and company name of car 
- Verified data types for all fields

## 📂 Files Included

- `car_data_cleaning.ipynb` – Jupyter Notebook with full cleaning process
- `cars_delhi.csv` –  Original dataset
- `car_cleaned_data.csv` – Cleaned version of the data

## 🙋‍♂️ About Me

This data was cleaned by Mrunmayee Hasabnis, a data enthusiast with experience in retail IT and a strong interest in data analytics and visualization

Connect with me on (www.linkedin.com/in/mrunmayee-hasabnis).
