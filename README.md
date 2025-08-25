# YouTube Trending Videos ETL Pipeline

This project implements an **ETL (Extract, Transform, Load) pipeline** for analyzing **YouTube Trending Videos**, built using **Microsoft Fabric Notebooks**.

## 🚀 Project Overview

The pipeline extracts trending YouTube video data, transforms it into a structured format, and prepares it for analysis and reporting.

### ETL Pipeline Steps

**1. Extract**  
- `youtube_extract_data1.ipynb`: Extracts YouTube trending data from APIs or datasets.  
- `youtube_extract_data2.ipynb`: Performs additional extraction and enrichment of raw data.

**2. Transform**  
- `youtube_transform_data.ipynb`: Cleans and structures the extracted data (e.g., normalizing fields, handling missing values, converting timestamps).

**3. Load (Optional)**  
- Load transformed data into **Microsoft Fabric Lakehouse** or **Warehouse** for downstream BI tools like **Power BI**.

---

## 🛠️ Tools & Technologies

- Microsoft Fabric (Notebooks, Lakehouse)  
- PySpark / Pandas (Data manipulation)  
- YouTube API / Dataset (Data source)  
- GitHub (Version control)

---

## 📊 Workflow in Microsoft Fabric

1. Create a Lakehouse in Microsoft Fabric.  
2. Upload or connect to the YouTube trending dataset / API.  
3. Run the extraction notebooks to pull and save raw data into Lakehouse tables.  
4. Run the transformation notebook to clean and model the data.  

---

## 📌 Future Improvements

- Automate the pipeline with Microsoft Fabric Data Pipelines.  
- Schedule daily or hourly refresh of data.  
- Extend transformations with sentiment analysis on video titles & descriptions.

---

## 🤝 Contributing

1. Fork this repository.  
2. Create a new branch (`feature-branch`).  
3. Commit your changes.  
4. Open a Pull Request.

---

## 📜 License

This project is open source under the MIT License.
