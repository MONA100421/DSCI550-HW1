# TEAM3-DSCI 550: BIGDATA Haunted Places Analysis

## 1. Overview
This project analyzes the **Haunted Places Dataset** by integrating additional datasets to explore patterns in paranormal activity. We use **Apache Tika** and **Tika Similarity** for data extraction, enhancement, and similarity analysis.

---
## 2. Team Members
- **Chen Yi Weng** ([wengchen@usc.edu](mailto:wengchen@usc.edu))
- **Aadarsh Sudhir Ghiya** ([aadarshs@usc.edu](mailto:aadarshs@usc.edu))
- **Zili Yang** ([ziliy@usc.edu](mailto:ziliy@usc.edu))
- **Niromikha Jayakumar** ([njayakum@usc.edu](mailto:njayakum@usc.edu))
- **Yung Yee Chia** ([yungyeec@usc.edu](mailto:yungyeec@usc.edu))
- **Colin Leahey** ([cleahey@usc.edu](mailto:cleahey@usc.edu))

---
## 3. Objectives
- Process and enhance the Haunted Places dataset.
- Extract new features such as evidence types, event details, and timestamps.
- Integrate three additional datasets of different MIME types.
- Perform similarity analysis using **Tika Similarity**.
- Generate a final dataset and analysis report.

---
## 4. Environment & Dependencies

### **(1) Required Libraries**
- **Python 3.x**
- **Pandas** (Data processing)
- **Apache Tika & Tika-Python** (Text analysis)
- **Tika Similarity** (Data similarity)
- **Datefinder** (Extract dates)
- **Number Parser** (Extract numbers)
- **NumPy, SciPy, Matplotlib, Seaborn** (Visualization & statistical analysis)

### **(2) Installation**
```bash
pip install -r Requirements.txt
```
---
## 5. File Structure
```
Data/
  ├── haunted_places.csv
  ├── 2020_USRC_Summaries.xlsx
  ├── alcohol_abuse.tsv
  ├── cleaned_crime_data.tsv
  ├── cleaned_haunted_places.tsv
  ├── counties.geojson
  ├── daylight_cleaned.csv
  ├── daylight_hours_full.tsv
  ├── daylight.csv
  ├── haunted_places_cleaned.csv
  ├── haunted_places_with_alcohol_daylight.tsv
  ├── haunted_places_with_alcohol.tsv
  ├── haunted_religious_crime_merged.csv
  ├── haunted_religious_historic_crime_merged.tsv
  ├── haunted_religious_merged.csv
  ├── historic_sites.csv
Source Code/
  ├── Preprocess.ipynb # Data Cleaning & Preprocessing Notebook
  ├── feature_extraction.ipynb
  ├── dataset_merging.ipynb
  ├── similarity_analysis.ipynb
Requirements.txt
README.md
TEAM_03_BIGDATA.pdf
```
---
## 6. Execution Steps

### **(1) Data Cleaning & Preprocessing**
```bash
jupyter notebook Source Code/Preprocess.ipynb
```

### **(2) Feature Extraction & Dataset Merging**
```bash
jupyter notebook Source Code/feature_extraction.ipynb
```

### **(3) Merge Additional Datasets**
```bash
jupyter notebook Source Code/dataset_merging.ipynb
```

### **(4) Similarity Analysis**
```bash
jupyter notebook Source Code/similarity_analysis.ipynb
```

### **(5) Visualization (Optional)**
```bash
jupyter notebook Source Code/visualization.ipynb
```

### **(6) Generate Final Report**
The final report will summarize findings, patterns, and visualizations.

---
## 7. Task Allocation

1. **Build up and manage the GitHub repository (including readme file)**  
   - **Chenyi**

2. **Add required fields to the datasets and provide analysis**  
   - **Data Cleaning & Analysis (Haunted_places)**: **Niromikha**, **Zili**  
   - **Alcohol Dataset**: **Yungyee**  
   - **Daylight Dataset**: **Yungyee**, **Chenyi**

3. **Find and append external datasets to the project**  
   - **Zili**: Religious Adherents Census Data  
   - **Chenyi**: Kaggle - US Crime Rates by County  
   - **Colin**: Historic Places dataset

4. **Tika Similarity Analysis**  
   - **Aadarsh**, **Zili**

5. **Documentation and filing**  
   - **Niromikha**
