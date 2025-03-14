# TEAM3-DSCI 550: BIGDATA Haunted Places Analysis

## 1. Overview
This project analyzes the **Haunted Places Dataset** by integrating additional datasets to explore patterns in paranormal activity. We use **Apache Tika** and **Tika Similarity** for data extraction, enhancement, and similarity analysis.

---
## 2. Team Members
- **Zili Yang** ([ziliy@usc.edu](mailto:ziliy@usc.edu))
- **Chen Yi Weng** ([wengchen@usc.edu](mailto:wengchen@usc.edu))
- **Aadarsh Sudhir Ghiya** ([aadarshs@usc.edu](mailto:aadarshs@usc.edu))
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
- **tika** (Apache Tika for text extraction)
- **number-parser** (Extract numbers)
- **datefinder** (Extract dates)
- **pandas** (Data processing)
- **numpy** (Numerical operations)
- **scipy** (Scientific computing)
- **jupyter** (Jupyter notebook)
- **seaborn** (Statistical data visualization)
- **matplotlib** (Plotting)
- **geopandas** (Geospatial data processing)
- **folium** (Leaflet maps)
- **pyogrio** (Geospatial data IO)
- **selenium** (Web scraping)
- **rtree** (Spatial indexing)
- **install-jdk** (Java Development Kit for Apache Tika)
- **libmagic** (File type detection)
- **csvkit** (CSV file handling)
- **editdistance** (Edit distance calculations)
- **BeautifulSoup** (HTML parsing for web scraping)

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
  ├── colheaders.conf
  ├── encoding.conf
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
---
## 7. Task Allocation

1. **Build up and manage the GitHub repository (including README file)**  
   - **Chen Yi**

2. **Add required fields to the datasets and provide analysis**  
   - **Data Cleaning & Analysis (Haunted_places): Niromikha, and Zili**  
   - **Alcohol Dataset: Yung Yee**  
   - **Daylight Dataset: Yung Yee, and Chen Yi**

3. **Find and append external datasets to the project**  
   - **Zili: Religious Adherents Census Data**  
   - **Chen Yi: US Crime Rates by County** 
   - **Colin: Historic Places dataset**

4. **Tika Similarity Analysis**  
   - **Aadarsh, and Zili**

5. **Documentation and filing**  
   - **Niromikha, and Yung Yee**
