# 🏏 T20 World Cup Analytics Dashboard

A data-driven **T20 World Cup Analytics Dashboard** developed using **Python and Microsoft Power BI** to analyze cricket matches, team performance, player statistics, batting, bowling, and ball-by-ball data.

The project transforms raw cricket datasets into structured analytical data using Python and Pandas, and then uses Power BI to create an interactive dashboard for exploring meaningful insights from T20 World Cup data.

---

## 📌 Project Overview

The **T20 World Cup Analytics Dashboard** provides a comprehensive view of cricket performance across multiple analytical dimensions.

The project combines **data processing, data modeling, and business intelligence** to convert raw cricket data into interactive visual insights.

The analysis covers:

* 🏆 Match and team performance
* 🏏 Batting statistics
* 🎯 Bowling statistics
* 👤 Player performance
* ⚾ Ball-to-ball analysis
* 📊 Comparative performance analysis
* 📈 Interactive Power BI visualizations

Python is primarily used for **data preparation and transformation**, while Power BI is used for **data modeling, analysis, and dashboard visualization**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Transform raw cricket data into structured datasets.
* Clean and prepare data using Python and Pandas.
* Analyze team and player performance.
* Explore batting and bowling statistics.
* Process ball-by-ball match information.
* Build an interactive Power BI dashboard.
* Demonstrate practical applications of **Data Analytics and Business Intelligence**.

---

## 🔄 Project Workflow

The complete project follows this analytics pipeline:

```text
Raw Cricket Data
       ↓
JSON Data Processing
       ↓
Python & Pandas
       ↓
Data Cleaning & Transformation
       ↓
Structured CSV Datasets
       ↓
Power BI Data Model
       ↓
Interactive Dashboard
       ↓
Cricket Performance Insights
```

The raw JSON files are processed using the Jupyter Notebook. The resulting structured CSV files are then used as analytical data sources for the Power BI dashboard.

---

## 🔍 Key Analysis

### 🏆 Match & Team Analysis

The dashboard provides insights into:

* Match results and outcomes
* Team-wise performance
* Match-level statistics
* Team comparisons
* Performance trends

### 🏏 Batting Analysis

The batting analysis focuses on:

* Runs scored
* Player batting performance
* Match-wise batting statistics
* Player comparisons
* Overall batting contribution

### 🎯 Bowling Analysis

The bowling analysis covers:

* Wickets
* Runs conceded
* Player bowling performance
* Bowling statistics
* Player comparisons

### 👤 Player Analysis

Player-level analysis includes:

* Player information
* Individual performance
* Batting records
* Bowling records
* Performance comparison

### ⚾ Ball-to-Ball Analysis

Detailed ball-by-ball data is processed to provide a deeper understanding of match events and player performance.

This enables analysis at a more granular level rather than relying only on final match statistics.

---

## 📊 Power BI Dashboard

The processed datasets are integrated into **Microsoft Power BI** to create an interactive analytics dashboard.

The dashboard allows users to explore:

* Team performance
* Match results
* Player statistics
* Batting performance
* Bowling performance
* Ball-by-ball information
* Comparative performance
* Interactive filters and visualizations

The goal is to convert large amounts of cricket data into **clear, interactive, and easy-to-understand visual insights**.

---

## 🛠️ Technologies Used

| Technology           | Purpose                                 |
| -------------------- | --------------------------------------- |
| **Python**           | Data processing and transformation      |
| **Pandas**           | Data cleaning and manipulation          |
| **NumPy**            | Numerical operations                    |
| **Matplotlib**       | Data visualization                      |
| **Seaborn**          | Statistical visualization               |
| **Jupyter Notebook** | Data preparation and analysis           |
| **Power BI**         | Dashboard and interactive visualization |
| **JSON**             | Raw cricket data                        |
| **CSV**              | Processed analytical datasets           |

---

## 📁 Project Structure

```text
T20-World-Cup-Analytics/
│
├── 📓 Ball To Ball.ipynb
├── 📊 T20 Analytics Dashboard.pbix
├── 📋 requirements.txt
│
├── 📄 Ball_to_Ball Analysis.pdf
├── 📄 B_to_B_Analysis.pdf
├── 📄 Paramaeter Scoping.pdf
│
├── 📂 Raw Data
│   ├── t20_wc_match_results.json
│   ├── t20_wc_batting_summary.json
│   ├── t20_wc_bowling_summary.json
│   └── t20_wc_player_info.json
│
└── 📂 Processed Data
    ├── dim_match_summary.csv
    ├── dim_players.csv
    ├── dim_players_no_images.csv
    ├── fact_bating_summary.csv
    └── fact_bowling_summary.csv
```

---

## 📦 Python Requirements

The project includes a `requirements.txt` file containing the required Python libraries with fixed versions.

```text
pandas==2.2.3
numpy==2.1.3
matplotlib==3.9.2
seaborn==0.13.2
jupyter==1.1.1
ipykernel==6.29.5
```

Pinning the package versions helps maintain a consistent and reproducible Python environment.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd T20-World-Cup-Analytics
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS / Linux**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Ball To Ball.ipynb
```

Run the notebook to perform the required data-processing and transformation steps.

---

## 📊 Open the Power BI Dashboard

After preparing the datasets, open:

```text
T20 Analytics Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

Refresh the data if required and explore the available dashboard pages, filters, and visualizations.

> **Note:** Power BI Desktop is required to open and interact with the `.pbix` file. Power BI is separate from the Python environment and is not installed through `requirements.txt`.

---

## 📈 Data Architecture

The project uses a structured analytical approach with dimension and fact datasets.

### Dimension Tables

* `dim_match_summary.csv`
* `dim_players.csv`
* `dim_players_no_images.csv`

These datasets primarily contain descriptive information about matches and players.

### Fact Tables

* `fact_bating_summary.csv`
* `fact_bowling_summary.csv`

These datasets contain measurable batting and bowling performance information used for analysis.

This structure helps organize the data efficiently for Power BI analysis and visualization.

---

## 💡 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning & Transformation
* Data Preparation
* Exploratory Data Analysis
* Python & Pandas
* NumPy
* JSON Data Processing
* CSV Data Processing
* Data Modeling
* Power BI
* Interactive Data Visualization
* Sports Analytics
* Business Intelligence

---

## 🚀 How to Use the Project

1. Clone the repository.
2. Set up the Python environment.
3. Install the dependencies using `requirements.txt`.
4. Open and run `Ball To Ball.ipynb`.
5. Verify the processed CSV datasets.
6. Open `T20 Analytics Dashboard.pbix` in Power BI Desktop.
7. Refresh the data if necessary.
8. Explore the interactive dashboard and analyze T20 World Cup performance.

---

## 📌 Project Category

**Sports Analytics • Data Analytics • Business Intelligence • Power BI • Python**

---

## 👨‍💻 Author

**Bansari Nimbalkar**

Computer Science & Data Science Graduate


---

⭐ If you found this project useful, consider giving the repository a star!
