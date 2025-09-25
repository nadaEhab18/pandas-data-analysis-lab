# 🐼 Pandas Data Analysis Lab 📊

> *Master data manipulation and analysis with Pandas using real-world datasets!* ✨

<div align="center">

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-FF6B6B?style=for-the-badge)
![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

</div>

## 🎯 Overview

A comprehensive collection of Pandas exercises using the MovieLens user dataset. This lab covers essential data manipulation techniques including data loading, exploration, filtering, grouping, and advanced analysis operations.

Perfect for data engineers, analysts, and anyone looking to strengthen their Pandas skills! 🚀

---

## 🛠️ Prerequisites

```
🐍 Python 3.x
🐼 Pandas library
📊 Basic understanding of data structures
💻 Your favorite code editor
```

## ⚡ Installation

### Install Required Libraries
```bash
pip install pandas
```

### Clone and Run
```bash
git clone https://github.com/yourusername/pandas-data-analysis-lab.git
cd pandas-data-analysis-lab
python pandas_lab.py
```

---

## 🎪 Lab Exercises

### 📥 **Data Loading and Setup (Steps 1-3)**
> Learn to import data with custom parameters and indexing
- Import Pandas library
- Load dataset from URL with pipe separator
- Set user_id as index

### 👀 **Data Exploration (Steps 4-10)**
> Get familiar with your dataset structure and contents
- View first 25 and last 10 entries
- Count observations and columns
- Examine column names and data types
- Understand dataset indexing

### 🔍 **Basic Data Operations (Steps 11-14)**
> Extract insights from individual columns
- Access specific columns
- Find unique values and most frequent items
- Generate statistical summaries

### 📊 **Group By Operations**
> Aggregate data for meaningful insights
- 👥 Count users by occupation
- ♂️♀️ Calculate average age by gender
- 📈 Find min/max/mean age for each occupation
- 📊 Calculate gender percentages by occupation

### 🔬 **Data Filtering**
> Filter data based on multiple conditions
- Filter by gender (female users)
- Filter by occupation (students and educators)
- Complex filtering (female users in their 20s)
- Geographic filtering (California zip codes)

### 🧠 **Complex Analysis**
> Advanced operations with pivot tables
- Create age decades from age data
- Build pivot table showing user count by occupation and age decade
- Cross-tabulation analysis

---

## 📊 Dataset Information

### 🎬 **MovieLens User Dataset**
- **Source:** https://raw.githubusercontent.com/justmarkham/DAT8/master/data/u.user
- **Records:** 943 users
- **Columns:** user_id, age, gender, occupation, zip_code
- **Format:** Pipe-separated values (|)

### 📈 **Sample Insights:**
- Most common occupation: Student
- Age range: 7-73 years
- Gender distribution: ~72% male, ~28% female
- Geographic spread: Across United States

<div align="center">

</div>
