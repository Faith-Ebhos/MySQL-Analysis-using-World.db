# 🌐 World Database SQL Analysis Project

This project leverages the **World Database** (commonly used in MySQL tutorials) to perform insightful data analysis using **SQL**. The dataset includes information about countries, cities, populations, governments, languages, and economies worldwide.

Using structured queries and complex joins, I analyzed global patterns related to population growth, regional distribution, official languages, government types, and economic indicators.

---

## 🗺️ Dataset Overview

The World Database consists of key tables:
- `Country`: country-level data (e.g., population, GNP, government form)
- `City`: urban centers linked to countries
- `CountryLanguage`: official and spoken languages
- `Continent`, `Region`: geographic groupings

---

## 🔍 Major Trends and Global Events Uncovered

- 🌍 **Asia Holds the Largest Population Share**: Over 55% of the world’s population is concentrated in Asia, with China and India leading by significant margins.
- 🏙️ **Urbanization on the Rise**: Countries with higher GNP per capita (e.g., Western Europe and North America) show larger urban populations relative to total population.
- 🗣️ **Multilingual Nations Are Common**: Countries like India, Belgium, and Switzerland officially recognize multiple languages, indicating cultural diversity.
- 🏛️ **Democracies Dominate**: Over 70% of the dataset's countries are listed with democratic government types, though population-wise, autocracies govern nearly half of the world’s people.
- 💰 **GNP Skewed Toward Few Countries**: A small number of countries contribute disproportionately to global GNP, reflecting global economic disparity.

---

## 🧠 SQL Skills Demonstrated

### 🔎 Data Retrieval and Filtering
- `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`, `DISTINCT`
- Extracted top countries by population, largest cities, and language counts

### 🔗 Relational Joins
- `INNER JOIN`, `LEFT JOIN` to combine `Country`, `City`, and `CountryLanguage`
- Linked cities with countries to compute total urban population per country

### 📊 Aggregation and Grouping
- `GROUP BY`, `HAVING`, `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`
- Calculated average GNP by continent, total speakers per language

### 🧮 Derived Columns and Subqueries
- Used subqueries to:
  - Identify countries where capital cities exceed national averages
  - Rank countries by population density
  - Compare GNP per capita to global median

### 🧱 Data Classification and Transformation
- `CASE WHEN` for custom classification (e.g., income levels)
- `CAST()` and `ROUND()` for formatting results

### 🧾 Views and Reusability
- Created SQL views for:
  - Top 10 most populous democratic nations
  - Language distribution across continents
  - Urban vs rural population ratios

---



[Data_Technician_Workbook_Week_3 Workbench Use (1).docx](https://github.com/user-attachments/files/20722557/Data_Technician_Workbook_Week_3.Workbench.Use.1.docx)
