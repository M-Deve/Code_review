# 📱 Smartphone Procurement Analytics

## Overview

This project simulates a real-world scenario in which a **Senior Data Scientist** collaborates with a **Junior Data Scientist** to assist a university's **procurement team** in selecting the best mobile phone for its employees. The objective was to clean and visualize smartphone data, ensure adherence to clean coding principles (like DRY), and validate data transformations through **unit testing**.

## 🧠 Project Context

As part of the university’s data team, you were tasked with:
- **Reviewing** a Junior Data Scientist's code.
- **Refactoring** redundant logic using a helper function.
- **Debugging and correcting** a failing unit test.
- **Ensuring code quality** with proper testing and best practices before the project is pushed to production.

## 🔧 Key Components

### 1. `prepare_smartphone_data()`
- Ingests and cleans smartphone data from a CSV file.
- Removes missing values.
- Prepares data for visualization.

### 2. `column_to_label()`
- Helper function to map DataFrame column names to more readable labels for plots.
- Refactored the plotting logic to use this function, eliminating repeated code blocks.

### 3. Data Visualization
- The cleaned dataset is used to plot smartphone attributes (e.g., RAM, battery, camera) against **price** to aid the procurement team's decision-making.

### 4. Unit Testing
- Fixed and improved the `test_nan_values()` function.
- Ensured the unit test aligns with the transformation logic in `prepare_smartphone_data()`.
- All tests are run using `pytest` and must exit with `ExitCode.OK`.

## ✅ Improvements Made
- Applied **DRY (Don't Repeat Yourself)** principles to reduce redundancy in the plotting function.
- Updated **print statements** to aid initial data inspection and later removed them for a production-ready version.
- Refactored and passed all **unit tests** ensuring code reliability.

## 🧪 How to Run

1. **Install dependencies** (if applicable):
   ```bash
   pip install pandas matplotlib pytest


## 👤 Author

**[Moyinoluwa Adisa]**  
Data Engineer | Python & SQL Enthusiast  
GitHub: [https://github.com/M-Deve] 
LinkedIn: [https://www.linkedin.com/in/moyinoluwaadisa] 
Email: adisamoyin@gmail.com
