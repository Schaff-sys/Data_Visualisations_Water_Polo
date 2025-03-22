# **Excel Data Processing: Club Natació Atlètic Barceloneta - Champions League Data**  

## **Overview**  
This Excel file serves as the **central data processing hub** for Club Natació Atlètic Barceloneta's **Water Polo Champions League** data from the **2023/24** and **2024/25** seasons. It collects multiple **CSV files**, merges them via **Power Query**, and applies data cleaning steps to ensure consistency and usability for further analysis in **Power BI and Tableau**.  

## **Key Features**  

### **1. CSV File Integration & Merging**  
- Uses **Power Query** to **import and combine multiple CSV files** into a single dataset.  
- Ensures seamless data updates when new CSVs are added to the source folder.  

### **2. Data Cleaning & Standardization**  
- Removes **duplicates and inconsistent formatting** across files.  
- Standardizes **date formats, player names, and team names**.  
- Converts key performance metrics into numerical values for accurate analysis.  

### **3. Enhanced Data Usability**  
- Adds **calculated columns** for derived metrics (e.g., Wastage = Balls Lost + Fouls Conceded).  
- Ensures all player statistics are in a format compatible with **Power BI and Tableau**.  

### **4. Ready for Visualization & Analysis**  
- The cleaned dataset is structured for **easy export** to **Power BI** and **Tableau**.  
- Maintains **flexibility** for additional transformations as needed.  

## **How to Use the File**  
1. **Add New Data**: Place new CSV files in the designated folder.  
2. **Refresh Power Query**: Click **Data → Refresh All** to update the merged dataset.  
3. **Check Cleaned Data Sheet**: Review the cleaned data before exporting for visualization.  
4. **Export to Power BI or Tableau**: Save the final dataset as a CSV for analysis.  

## **Future Improvements**  
- Automate **error handling** for missing or incorrectly formatted data.  
- Implement **automated updates** when new CSV files are added.  
- Create additional **validation checks** to prevent data inconsistencies.  

## **License**  
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.  

