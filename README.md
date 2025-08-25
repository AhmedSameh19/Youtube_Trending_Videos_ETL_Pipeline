YouTube Trending Videos ETL Pipeline

This project implements an ETL (Extract, Transform, Load) pipeline for analyzing YouTube Trending Videos, built using Microsoft Fabric Notebooks.

🚀 Project Overview

The main goal is to extract trending YouTube video data, transform it into a structured format, and prepare it for analysis and reporting.

The pipeline follows these steps:

Extract

youtube_extract_data1.ipynb: Extracts YouTube trending data from source APIs/files.

youtube_extract_data2.ipynb: Performs additional extraction and enrichment of raw data.

Transform

youtube_transform_data.ipynb: Cleans, transforms, and structures the extracted data for further analysis (e.g., normalizing fields, handling missing values, converting timestamps).

Load (Optional)

Data can be loaded into Microsoft Fabric Lakehouse or Warehouse for downstream BI tools such as Power BI.

🛠️ Tools & Technologies

Microsoft Fabric (Notebooks, Lakehouse)

PySpark / Pandas (data manipulation)

YouTube API / Dataset (data source)

GitHub (version control)


📊 Workflow in Microsoft Fabric

Create a Lakehouse in Microsoft Fabric.

Upload or connect the YouTube trending dataset / API.

Run the extraction notebooks to pull and save raw data into Lakehouse tables.

Run the transformation notebook to clean and model the data.

📌 Future Improvements

Automate the pipeline with Microsoft Fabric Data Pipelines.

Add scheduling for daily or hourly refresh.

Extend transformations with sentiment analysis on video titles & descriptions.

🤝 Contributing

Fork this repository.

Create a new branch (feature-branch).

Commit your changes.

Open a Pull Request.

📜 License

This project is open source and available under the MIT License.
