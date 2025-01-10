# Baseball Stats Pipeline Project

## Why a Baseball Stats Pipeline?
As a lifelong baseball fanatic and former collegiate player, I’ve always been passionate about analyzing the game through data. Baseball, with its vast datasets and rich statistics, is a perfect match for any data enthusiast. This project stemmed from my desire to build a reliable data pipeline that I can use to generate insights and support my baseball analyses for a future blog. 

For a detailed narrative of the project, including the motivation and challenges faced, refer to the **[Project Writeup](./project%20writeup.pdf)**.

---

## Project Overview
The Baseball Stats Pipeline automates the collection, transformation, and storage of baseball statistics using Python, Airflow, and GCP. It creates a robust relational database for querying and analysis. For an overview of the project methodology and key outcomes, see the **[Project Presentation](./Project%20presentation.pdf)**.

---

## Key Features
- **Data Generation**:
  - Used the Pybaseball package to scrape advanced stats from Fangraphs and MLB APIs.
  - Managed challenges with inconsistent player IDs across websites.
- **Data Ingestion**:
  - Designed ingestion functions to fetch and format data for compatibility with the database schema.
  - Automated future ingestions using Airflow workflows.
- **Data Transformation**:
  - Integrated data transformations directly into ingestion steps to align datasets with the ERD structure.
- **Data Storage**:
  - Stored data in Google Cloud Platform (GCP) for scalability and accessibility.
- **Data Serving**:
  - Created a 3NF relational database that allows easy and efficient querying for analysis.

For more information on these features and the technical implementation, refer to the **[Project Presentation](./Project%20presentation.pdf)**.

---

## Final ERD
The project resulted in a simplified but functional ERD that structures baseball statistics for analysis:
- **Tables** include player stats, game logs, and advanced metrics.
- See the ERD details in the **[Project Writeup](./project%20writeup.pdf)**.

---

## Challenges and Future Work
- **Challenges**:
  - Inconsistent player IDs across different data sources.
  - Limited availability of certain advanced statistics.
  - Adjusting the ERD due to gaps in available data.
- **Future Plans**:
  - Expand the ERD to include additional data like player contracts and career history.
  - Resolve ID inconsistencies across data sources for seamless integration.

For further insights into the challenges and next steps, review the **[Project Writeup](./project%20writeup.pdf)**.

---

## Retrospective
This project was a transformative experience, allowing me to apply classroom concepts to a personal passion. The resulting pipeline enables me to explore and analyze baseball data efficiently, and it will serve as the backbone for future projects.

For a summary of the project objectives, methodology, and outcomes, visit the **[Project Presentation](./Project%20presentation.pdf)**.
