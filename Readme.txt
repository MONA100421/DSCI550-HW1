# DSCI 550: BIGDATA Haunted Places Analysis

## 1. Overview
This project analyzes the **Haunted Places Dataset** by integrating additional datasets to explore patterns in paranormal activity. We use **Apache Tika** and **Tika Similarity** for data extraction, enhancement, and similarity analysis.

---
## 2. Objectives
- Process and enhance the Haunted Places dataset.
- Extract new features such as evidence types, event details, and timestamps.
- Integrate three additional datasets of different MIME types.
- Perform similarity analysis using **Tika Similarity**.
- Generate a final dataset and analysis report.

---
## 3. Environment & Dependencies

### **(1) Required Tools & Libraries**
- **Python 3.x**
- **Pandas** (Data processing)
- **Apache Tika & Tika-Python** (Text analysis)
- **Tika Similarity** (Data similarity)
- **Datefinder** (Extract dates)
- **Number Parser** (Extract numbers)

### **(2) Installation**
```bash
pip install pandas tika tika-similarity datefinder number-parser
```

---
## 4. File Structure
```
├── Data/
│   ├── haunted_places.tsv
│   ├── dataset1.csv
│   ├── dataset2.json
│   ├── dataset3.xml
│
├── Source Code/
│   ├── preprocess.py
│   ├── feature_extraction.py
│   ├── dataset_merging.py
│   ├── similarity_analysis.py
│   ├── visualization.ipynb
│
├── Report.pdf
├── README.txt
├── Requirements.txt
```

---
## 5. Execution Steps

### **(1) Convert CSV to TSV**
```bash
python Source Code/preprocess.py
```

### **(2) Feature Extraction**
```bash
python Source Code/feature_extraction.py
```

### **(3) Merge Additional Datasets**
```bash
python Source Code/dataset_merging.py
```

### **(4) Similarity Analysis**
```bash
python Source Code/similarity_analysis.py
```

### **(5) Visualization (Optional)**
```bash
jupyter notebook Source Code/visualization.ipynb
```


