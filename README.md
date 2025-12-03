# ElectionDataAnalysis

This project collects election data from [Election Commission of Bangladesh](https://www.ecs.gov.bd/page/result-for-12th-national-parliament-election).

## Overview

The goal of this project is to gather, process, and analyze election data to extract meaningful insights. The workflow includes:

1. **Data Collection**  
   - Using **web scraping** to collect data on constituencies, candidates, polling centers, and votes.

2. **Data Processing**  
   - Cleaning and transforming the data using **Python** and **pandas**.
   - Handling composite keys, removing redundant columns, and ensuring data integrity.

3. **Data Analysis & Visualization**  
   - Aggregating and summarizing key statistics.
   - Creating visualizations to highlight trends, voter turnout, and candidate performance.

## Key Features

- Consolidation of multiple raw data files into structured datasets.
- Detection and removal of duplicate or redundant data.
- Extraction of key attributes for analysis (e.g., constituency number, candidate number, votes).
- Flexible structure for easy extension and further analysis.

## Tools & Libraries

- Python 3.x  
- pandas  
- matplotlib / seaborn (for visualization)  
- requests / BeautifulSoup (for web scraping)  

## Project Workflow

1. **Scrape election results** from the official website.
2. **Store raw data** in Excel files.
3. **Clean and preprocess** the data:
   - Separate numbers and names into distinct columns.
   - Remove redundant columns like constituency, polling center, candidate name (if needed for analysis).
4. **Analyze and visualize** results to identify key insights.

## Dataset

The project produces the following main files:

- `Seat_Names.xlsx` – List of constituencies.
- `Polling_Centers.xlsx` – Details of polling centers.
- `All_Candidates.xlsx` – Candidate information.
- `Cast_Votes.xlsx` – Votes cast for each candidate.

## Usage

1. Clone the repository:  
```bash
git clone <repository-url>
