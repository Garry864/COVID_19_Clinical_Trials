# 🦠 COVID-19 Clinical Trials Analysis

Welcome to the **COVID-19 Clinical Trials Analysis** repository! This project provides an in-depth exploration of 5,783 COVID-19 clinical trials, uncovering trends, insights, and relationships to better understand the global research landscape during the pandemic.

📄 **Hosted Analysis Report**:  
[Explore the Full Report](https://garry864.github.io/COVID_19_Clinical_Trials/)

---

## 📖 Project Overview

The dataset comprises records of clinical trials focusing on COVID-19. Each trial contains details like its title, status, interventions, outcome measures, sponsors, and collaborators. This analysis leverages Exploratory Data Analysis (EDA) and visualization techniques to uncover patterns and derive actionable insights.

---

## ✨ Key Insights

### 1️⃣ **Clinical Trial Landscape**
- **Total Trials**: 5,783.
- **Dominant Status**: "Recruiting" trials (2,095), followed by "Not yet recruiting" (1,224).
- **Most Common Trial Phase**: "Unknown," particularly within the "Recruiting" status.

### 2️⃣ **Time Series Trends**
- Most trials were initiated **post-2019**, reflecting the global response to the COVID-19 pandemic.
- A noticeable spike in research activities followed the pandemic's outbreak.

### 3️⃣ **Location Analysis**
- **Top Countries by Trial Count**:
  1. United States: 1,287 trials.
  2. France: 647 trials.
  3. United Kingdom: 585 trials.
- Countries with fewer trials often exhibit higher percentages of missing data in the "Acronym" feature.

### 4️⃣ **Missing Data**
- Features like "Acronym," "Results First Posted," and "Study Documents" have a significant percentage of missing values.
- **Handling Missing Data**:
  - Imputation by a missing indicator.
  - Median imputation for numerical features.
  - "Missing feature" label for categorical variables.

### 5️⃣ **Data Relationships**
- **Study Status vs. Trial Phase**:
  - "Recruiting" status dominates across various phases.
  - The "Unknown" phase is most prevalent in recruiting trials.

---

## 🔍 Exploratory Data Analysis (EDA)

### **Univariate Analysis**
- Examines distributions of individual variables.
- Highlights that "Recruiting" is the most frequent study status.

### **Bivariate Analysis**
- Explores relationships between variables like study status and trial phase.
- Visualizes insights using bar plots, histograms, and scatter plots.

### **Time Series Analysis**
- Tracks the number of trials initiated over time, showing a surge after 2019.

### **Geographical Distribution**
- Extracts country-level information to analyze global research activity.
- Visualized with maps and bar charts for easy interpretation.


## 📂 Repository Contents

---

## 🚀 How to Use

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/garry864/COVID_19_Clinical_Trials.git
cd COVID_19_Clinical_Trials
```

### 2️⃣ Install Dependencies
Ensure Python is installed and set up the required environment:
```bash
pip install -r requirements.txt
```

### 3️⃣ Explore the Data
- Open the **hosted report**: [COVID-19 Clinical Trials Report](https://garry864.github.io/COVID_19_Clinical_Trials/).
- Run the scripts in the `/src/` folder to reproduce or expand the analysis.

---

## 🌟 Key Features of the Analysis

1. **Comprehensive EDA**: 
   - Visualizes trends, distributions, and relationships in the data.
2. **Handling Missing Data**: 
   - Various imputation techniques are applied to deal with missing values.
3. **Geographical Insights**: 
   - Highlights country-level research activity.
4. **Time Series Analysis**: 
   - Tracks the growth in trials over time with compelling visualizations.

---

## 📊 Future Exploration Opportunities

- **Impact Analysis**: Investigate the effect of funding or policy changes on trial status.
- **Trial Outcomes**: Analyze completed trials for outcome effectiveness.
- **Global Collaboration**: Explore collaboration networks between sponsors and investigators.
- **Trend Analysis**: Compare COVID-19 research trends with other diseases.

---

## 🤝 Contributions

Contributions are highly welcome! Whether it's improving the code, adding more visualizations, or providing new insights, feel free to fork the repository and submit a pull request.

---

## 📧 Contact

For inquiries or collaborations, reach out through the [GitHub profile](https://github.com/garry864).

