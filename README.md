# Bihar Electoral Data Analysis

## Overview

This project presents a detailed electoral data analysis of Bihar Assembly Elections across multiple election years using Python-based data analysis workflows. The notebook focuses on constituency-level and state-level electoral trends, vote share movements, swing constituencies, party strongholds, and competitive seat analysis.

The analysis was performed using structured electoral datasets and includes exploratory data analysis, aggregation logic, trend analysis, and political insights generation.

---

## Objectives

The project answers multiple election-analysis questions such as:

* Determining winning parties at the state level across elections
* Identifying swing constituencies where winners changed in every election
* Finding the top-performing parties by vote share
* Detecting party strongholds and growing constituencies
* Identifying close contest seats
* Analyzing consistently tri-polar constituencies
* Tracking vote growth trends across elections

---

## Dataset

The analysis uses Bihar Assembly Election results across the following elections:

* February 2005
* October 2005
* 2010
* 2015

The dataset contains constituency-wise election information including:

* Constituency details
* Candidate names
* Political parties
* Votes secured
* Vote share percentages
* Election year information

---

## Tech Stack

* **Python**
* **Pandas** – Data cleaning and aggregation
* **NumPy** – Numerical operations
* **Matplotlib / Seaborn** – Visualization
* **Jupyter Notebook** – Analysis environment

---

## Key Analysis Performed

### 1. State-Level Winning Party Analysis

Calculated total votes secured by each political party across Bihar for every election year to determine the overall leading party.

### 2. Swing Seat Identification

Detected constituencies where different parties won in every election cycle, highlighting volatile voter behavior.

### 3. Top Performing Parties

Identified the top 8 parties in each election based on total votes secured at the state level.

### 4. Minimum Historical Vote Analysis

Analyzed the minimum vote performance of major parties across all elections and constituencies.

### 5. Tri-Polar Constituency Detection

Found constituencies where 3 or more parties consistently received more than 10% vote share in every election.

### 6. Stronghold Seat Analysis

Identified constituencies repeatedly won by the same political party across all elections.

### 7. Close Contest Analysis

Detected constituencies where the winning margin between the top two candidates remained below 10–15% across elections.

### 8. Growing Constituency Analysis

Tracked constituencies where parties continuously increased their vote count in subsequent elections.

---

## Major Insights

### Election Trends

* Rashtriya Janata Dal (RJD) dominated vote share during the 2005 elections.
* Janata Dal (United) emerged strongly in the 2010 elections.
* Bharatiya Janata Party (BJP) showed significant electoral performance in the 2015 elections.

### Swing Constituencies

Several constituencies displayed highly dynamic voting behavior with different winning parties in each election cycle, indicating politically competitive regions.

### Stronghold Seats

Some constituencies consistently remained loyal to specific parties such as:

* Bharatiya Janata Party (BJP)
* Janata Dal (United)

These constituencies showed stable voting patterns across elections.

### Competitive Electoral Landscape

Multiple constituencies exhibited close contests with very small victory margins, highlighting highly competitive political environments.

### Multi-Party Competition

The analysis also identified tri-polar constituencies where more than three parties maintained meaningful vote share presence consistently.

---

## Project Structure

```bash
Bihar_Electoral_Data_Analysis/
│
├── Bihar_election_result_Electoral_data_Analysis.ipynb
├── datasets/
├── outputs/
└── README.md
```

---

## Sample Use Cases

This project can be useful for:

* Political campaign analysis
* Electoral trend forecasting
* Constituency competitiveness analysis
* Vote share movement studies
* Political data science projects
* Election strategy and reporting

---

## Future Improvements

Potential enhancements for the project:

* Interactive dashboards using Streamlit or Power BI
* Predictive modeling for election forecasting
* GIS-based constituency mapping
* Candidate-level performance analysis
* Caste and demographic integration
* Coalition impact analysis

---

## Conclusion

This project demonstrates how electoral datasets can be transformed into actionable political insights using data analytics techniques. The notebook combines constituency-level analysis with state-wide trend exploration to understand voting behavior, party performance, and electoral competitiveness in Bihar Assembly Elections.

---

## Author

**Prajay Urkude**

Political Data Analyst | Electoral Analytics | AI & Data-Driven Political Intelligence
