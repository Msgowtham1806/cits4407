
# CITS4407 Assignment 2  
### *“Board Games **
**Date:** 19 May 2025  
**Author:** Madipalli Sriram Gowtham  
**Student ID:** 24847446  
**Course:** CITS4407 – Open Source Tools and Scripting  

---

## 📂 Project Structure & Description

This repository contains scripts developed for analyzing board game datasets as part of the CITS4407 assignment. The analysis explores data cleaning, empty cell detection, and statistical insights into board game mechanics and domains.

- **empty_cells**  
  A script that scans a delimiter-separated data file and reports the count of empty (blank or whitespace-only) cells in each column. Designed to handle tricky cases like non-ASCII characters and inconsistent delimiters.

- **preprocess**  
  Cleans and normalizes a raw `;`-delimited dataset by converting it into a tab-separated (TSV) format. Fixes mixed line endings, standardizes decimal points (comma → dot), removes non-ASCII characters, and fills missing IDs with new unique values.

- **analysis**  
  Performs the core data analysis: identifies the most popular game mechanics and domains, and calculates Pearson correlation coefficients to reveal relationships in the cleaned dataset.

- **README.md**  
  This documentation file explaining project details, usage, and testing notes.

---

=======
CITS4407 Assignment 2
*“Board Games **
Date: 19 May 2025
Author: Madipalli Sriram Gowtham
Student ID: 24847446
Course: CITS4407 – Open Source Tools and Scripting

📂 Project Structure & Description
This repository contains scripts developed for analyzing board game datasets as part of the CITS4407 assignment. The analysis explores data cleaning, empty cell detection, and statistical insights into board game mechanics and domains.

empty_cells
A script that scans a delimiter-separated data file and reports the count of empty (blank or whitespace-only) cells in each column. Designed to handle tricky cases like non-ASCII characters and inconsistent delimiters.

preprocess
Cleans and normalizes a raw ;-delimited dataset by converting it into a tab-separated (TSV) format. Fixes mixed line endings, standardizes decimal points (comma → dot), removes non-ASCII characters, and fills missing IDs with new unique values.

analysis
Performs the core data analysis: identifies the most popular game mechanics and domains, and calculates Pearson correlation coefficients to reveal relationships in the cleaned dataset.



