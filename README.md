# DSCI 550: BIGDATA Haunted Places Analysis

## 1. Overview
This project analyzes the **Haunted Places Dataset** by integrating additional datasets to explore patterns in paranormal activity. We use **Apache Tika** and **Tika Similarity** for data extraction, enhancement, and similarity analysis.

---
## 2. Team Members
- **Chen Yi Weng** (wengchen@usc.edu)
- **Aadarsh Sudhir Ghiya** (aadarshs@usc.edu)
- **Zili Yang** (ziliy@usc.edu)
- **Niromikha Jayakumar** (njayakum@usc.edu)
- **Yung Yee Chia** (yungyeec@usc.edu)
- **Colin Leahey** (cleahey@usc.edu)

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

### **(1) Required Tools & Libraries**
- **Python 3.x**
- **Pandas** (Data processing)
- **Apache Tika & Tika-Python** (Text analysis)
- **Tika Similarity** (Data similarity)
- **Datefinder** (Extract dates)
- **Number Parser** (Extract numbers)
- **NumPy, SciPy, Matplotlib, Seaborn** (Visualization & statistical analysis)

### **(2) Installation**
```bash
pip install pandas tika tika-similarity datefinder number-parser numpy scipy matplotlib seaborn
```

---
## 5. File Structure
```
├── Data/
│   ├── haunted_places.csv
│   ├── alcohol_abuse.tsv
│   ├── daylight_hours_full.tsv
│   ├── haunted_places_with_alcohol.tsv
│   ├── haunted_places_with_alcohol_daylight.tsv
│
├── Source Code/
│   ├── Preprocess.ipynb  # Data Cleaning & Preprocessing Notebook
│   ├── Script1.py        # Feature Extraction & Integration
│   ├── README.md         # Project Documentation
│   ├── Requirements.txt  # Dependencies
│
├── Report.pdf  # Final Report
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

