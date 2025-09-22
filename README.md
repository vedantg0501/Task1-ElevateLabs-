# Task1-ElevateLabs-
Data Cleaning and Preprocessing
Task1-ElevateLabs - Data Cleaning and Preprocessing
A small project for Day 1 tasks at Elevate Labs. This repository contains a Jupyter Notebook that demonstrates data cleaning and preprocessing on a medical appointment dataset.

Table of contents
Description

Features

Prerequisites

Setup

Usage

Project structure

Contact

Description
This repository holds the code and resources for a data cleaning and preprocessing task. The main goal is to clean a dataset of medical appointments to make it suitable for analysis. The process involves handling missing values, duplicates, and formatting issues.

Features
Data Loading: The dataset is loaded from a CSV file into a pandas DataFrame.

Handling Duplicates: Duplicate records are removed to ensure data integrity.

Handling Inconsistent Data: The code identifies and removes a record with an invalid age (-1).

Data Type Conversion: The 'ScheduledDay' column is converted to a proper datetime format.

Column Renaming: Column names are standardized for clarity ('Hipertension' to 'Hypertension' and 'No-show' to 'No_show').

Prerequisites
Python 3

pandas

Jupyter Notebook or Jupyter Lab

Setup
Clone the repository:

Bash

git clone <repo-url>
Change into the project directory:

Bash

cd "d:\Elevate Labs\Task1(day1)"
Install dependencies:

Bash

pip install pandas
Usage
Open and run the dataCleaning&preprocessing.ipynb notebook in Jupyter Notebook or Jupyter Lab.

The notebook contains step-by-step code for cleaning and preprocessing the data.

Project structure
README.md — this file

dataCleaning&preprocessing.ipynb — Jupyter Notebook with the data cleaning code

Medical_Appointment_No_Shows.csv — The dataset used in the notebook

Contact
For questions, open an issue or contact the repository owner or mail at vedantgupta8784@gmail.com.
