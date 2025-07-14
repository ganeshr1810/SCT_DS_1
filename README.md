# SCT_DS_1
# Population Distribution Visualization – Task 01

---

This project visualizes the **distribution of India's population by age groups (2022)** using a bar chart. The task demonstrates data extraction, preprocessing, and visual representation of categorical data.

---

## Objectives

- **Extract** a population dataset from a ZIP archive (CSV format)  
- **Identify and clean** relevant columns containing age groups and percentages  
- **Visualize** the population distribution using a **bar chart**  
- Use fallback data if the dataset is missing or corrupted  
- Display age-wise distribution with clear labels and color-coded bars  

---

## Workflow Summary

1. Upload a ZIP file containing the dataset (CSV format)  
2. Extract and read the CSV file using Python's `zipfile` and `pandas`  
3. Detect age group and percentage columns automatically  
4. Clean and standardize data values  
5. If the dataset is invalid, use the following fallback sample:  

    | Age Group   | Percentage |
    |-------------|------------|
    | 0–20 Years  | 34.1%      |
    | 21–44 Years | 57.0%      |
    | 45+ Years   | 6.7%       |

6. Create a **bar chart** using `matplotlib` with appropriate formatting and labeling  
7. Display the chart in the notebook environment (Google Colab)  

---

## Technologies Used

- `Python 3.x`  
- `pandas` – for data handling  
- `matplotlib` – for visualization  
- `zipfile`, `io` – for file extraction and handling  
- Google Colab for interactive execution  

---

## Evaluation

- ✅ Data is successfully extracted and cleaned from the uploaded ZIP file  
- ✅ Chart provides a clear, well-labeled, and color-coded visualization  
- ✅ Script handles invalid or missing datasets gracefully using fallback values  
- ✅ Code is modular with functions for readability and reuse  

---

## Notes

- Ensure that the uploaded ZIP file contains a valid `.csv` file with columns representing **age groups** and **population percentages**  
- Inconsistent or misnamed columns may lead to fallback data being used  
- Bar colors and labels are customizable within the `create_population_chart` function  
- The code is structured for use in **Google Colab**; modifications may be required for other environments  

---
