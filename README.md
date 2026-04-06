# 🌍 Global Indicators: Data Extraction Project

This project focuses on **Data Extraction** and **Insight Generation** from a comprehensive global dataset containing 64 indicators for 194 countries. The goal was to clean the raw data structure and extract meaningful information using Python and Pandas.

## 📂 Project Structure
- `Countries.csv`: The raw dataset with socio-economic, energy, and demographic indicators.
- `countries.ipynb`: The Jupyter Notebook containing extraction logic and analysis.

## 🛠️ Operations Performed
I performed the following tasks to make the data usable:
1. **Cleaning Column Headers:** Standardized 64 column names for easier coding.
2. **Custom Text Extraction:** Used logic to identify "Republics" from official country names.
3. **Regional Analysis:** Filtered and counted countries based on regions (e.g., Eastern Europe, Africa).
4. **Leader Identification:** Extracted political leaders and handled unknown values.
5. **Key Demographic Insights:** 
   - Found the **Highest & Lowest Populated** countries and their capitals.
   - Identified the **Top 5 Democracy Scores** globally.
   - Compared **Population vs. GDP** for the top 10 most populated nations.

## 📊 Quick Findings from Extraction
- **Total Republics:** 125 countries identified with "Republic" in their name.
- **Population Leader:** Found the country with the highest population and its capital.
- **Economic Insight:** Compared how the world's most populated countries rank in terms of GDP.

## 🚀 Libraries Used
- **Pandas**: For data frame manipulation and filtering.
