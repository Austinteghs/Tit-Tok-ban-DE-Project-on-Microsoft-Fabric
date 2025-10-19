# End-to-End Data Engineering Project with Microsoft Fabric

## Project Overview
This project demonstrates an **End-to-End Data Engineering workflow using Microsoft Fabric**. It includes data ingestion, transformation, sentiment analysis, pipeline orchestration, and reporting using Power BI. The project was undertaken as a **follow-up to my Microsoft Fabric Analytics Engineer Certification (DP-600)** to reinforce my understanding of Fabric’s capabilities.

## Project Goals
- Demonstrate the ability to work with **Microsoft Fabric** for data engineering.
- Handle **data ingestion** from external sources with **Microsoft Data Factory**.
- Perform **data transformation** and **incremental loading** using **Synapse Data Engineering** and **Spark Notebooks**.
- Conduct **sentiment analysis** using **Synapse Data Science**.
- Build a **Power BI dashboard** to visualize key insights.
- Automate workflows with **Data Factory pipelines**.
- Implement **alerts and monitoring** using **Data Activator**.

## Project Highlights
- Worked around **Azure student account limitations** and API constraints that restricted data ingestion to ~150 rows per request.
- Ingested data on the **TikTok ban** from the **Bing Search API**.
- Applied **data transformations** and **sentiment analysis** to extract insights.
- Created a **Power BI dashboard** to visualize sentiment trends and demonstrate the integration of **data engineering with reporting**.
- Designed an **end-to-end data pipeline** to simulate real-world **data engineering workflows**.

## Tools & Technologies Used
- **Microsoft Fabric**
- **Synapse Analytics**
- **Data Factory**
- **Power BI**
- **Spark Notebooks** (for incremental loads & transformations)
- **Data Activator** (for alerts and monitoring)
- **Bing Search API** (for data ingestion)

## Project Architecture
The project consists of the following key phases:
1. **Data Ingestion**: Extracting news articles related to the TikTok ban using **Bing Search API**.
2. **Data Transformation**: Processing and structuring data using **Synapse Data Engineering**.
3. **Incremental Load**: Using **Spark Notebooks** to efficiently update data without full reloads.
4. **Sentiment Analysis**: Implementing **Synapse Data Science** for sentiment scoring.
5. **Data Visualization**: Creating an **interactive Power BI report** to present insights.
6. **Pipeline Orchestration**: Automating workflows using **Data Factory**.
7. **Alerts & Monitoring**: Setting up real-time alerts with **Data Activator**.
   
![Architecture Diagram](https://github.com/Austinteghs/Tit-Tok-ban-DE-Project-on-Microsoft-Fabric/blob/main/architecture%20diagram.gif?raw=true)

## Folder Structure
```
📂 Microsoft-Fabric-Data-Engineering-Project
│-- 📜 README.md  # Project Documentation
│-- 📂 data       # Sample data files
│-- 📂 notebooks  # Spark Notebooks for transformations & incremental loading
│-- 📂 reports    # Power BI dashboards
│-- 📂 pipelines  # Data Factory pipeline configurations
│-- 📂 scripts    # Python scripts for API calls & data processing
```

## Power BI Dashboard
The Power BI report provides insights on:
- **Overall sentiment** of news articles on the TikTok ban.
- **Trends over time** showing changes in public sentiment.
- **Geographical insights** on how different regions report on the topic.
![PowerBi Dashboard](https://raw.githubusercontent.com/Austinteghs/Tit-Tok-ban-DE-Project-on-Microsoft-Fabric/refs/heads/main/Tik%20Tok%20ban%20Dashboard.png)


## How to Run This Project
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/Microsoft-Fabric-Data-Engineering-Project.git
   ```
2. Configure the **Bing Search API key** in the `scripts` folder.
3. Deploy **Data Factory pipelines** using provided templates.
4. Run **Spark Notebooks** in **Microsoft Fabric** to process data.
5. Open the **Power BI report** to visualize results.

## YouTube Walkthrough
I have documented the entire process on my YouTube channel **Tech Bro Eghosa**. Watch the full playlist here: [YouTube Playlist](https://www.youtube.com/playlist?list=PL9lLozRY3qaDR2cCKjK6eRRWq5iBpXwT4)

## Future Enhancements
- Implement **real-time streaming** for data ingestion.
- Optimize **incremental loads** for larger datasets.
- Deploy the project using **Azure DevOps** for CI/CD automation.

## Next Steps
I am now preparing for the **Microsoft Certified: Fabric Data Engineer Associate (DP-700)** certification to further deepen my expertise in Microsoft Fabric.

---
**Feel free to explore the project and provide feedback or suggestions!** 🚀

#MicrosoftFabric #DataEngineering #PowerBI #DP600 #SynapseAnalytics

