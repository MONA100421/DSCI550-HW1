# DSCI 550: BIGDATA Haunted Places Analysis

## 1. Overview
This project explores the **Haunted Places Dataset**, integrating additional datasets to analyze paranormal activity patterns. The dataset consists of **21,983 rows and 10 columns** containing location-based and descriptive data. The goal is to preprocess, extract features, merge multiple datasets, and conduct similarity analysis using **Apache Tika** and **Tika Similarity**.

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
- **Data Cleaning**: Remove missing values and incorrect entries.
- **Enhance Geographic Data**: Add county-level location information.
- **Feature Extraction**: Extract haunted evidence types, event details, and timestamps.
- **Dataset Integration**: Merge at least three external datasets of different **MIME types**.
- **Similarity Analysis**: Use **Tika Similarity** for clustering and pattern detection.
- **Final Report**: Generate a dataset and an analysis report.

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
│── Data/
│   ├── haunted_places.csv
│
│── Source Code/
│   ├── Preprocess.ipynb # Data Cleaning & Preprocessing Notebook
│   ├── Script1.py
│   ├── alcohol_abuse.tsv
│   ├── daylight_hours_full.tsv
│   ├── haunted_places.tsv
│   ├── haunted_places_with_alcohol.tsv
│   ├── haunted_places_with_alcohol_daylight.tsv
│   ├── notebook w_4GI.ipynb
│   ├── notebook.ipynb
│
│── README.md
│── Readme.txt
│── Requirements.txt
│── TEAM3_BIGDATA.pdf
```
---
## 6. Execution Steps

### **(1) Data Cleaning & Preprocessing**
```bash
jupyter notebook Source Code/Preprocess.ipynb
```

### **(2) Feature Extraction & Dataset Merging**
```bash
python Source Code/Script1.py
```

### **(3) Similarity Analysis (Optional)**
```bash
python Source Code/similarity_analysis.py
```

### **(4) Generate Final Report**
The final report will summarize findings, patterns, and visualizations.
