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
