# ✈️ Airline Delay Root Cause Analysis (5.8M Flights)

## 📌 Project Overview
This project analyzes 5.8 million US flight records (2015 dataset) to identify the major root causes of flight delays and seasonal patterns.

The objective was to:
- Identify the most impactful delay causes
- Analyze correlation with arrival delay
- Study monthly trends
- Perform normalized seasonal analysis

---

## 📊 Dataset
- 5,819,079 flight records
- 31 features
- ~1.3GB dataset
- Year: 2015 US Flights

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Correlation Analysis
- Data Cleaning & Missing Value Handling

---

## 🔎 Key Findings
- Late aircraft delay is the largest contributor to total delay minutes
- Airline delay has the strongest correlation with arrival delay
- June & July show peak seasonal delays
- Security delay has minimal impact

---

## 📈 Visualizations
- Total Delay by Root Cause (Bar Chart)
- Correlation Heatmap
- Seasonal Delay Heatmap
- Monthly Flight Volume Analysis

- ---

## 🚀 How to Run This Project

### 1️⃣ Clone the repository

git clone https://github.com/manasa-mv/Airline-Delay-Root-Cause-Analysis.git
cd Airline-Delay-Root-Cause-Analysis

### 2️⃣ Install required libraries

pip install pandas numpy matplotlib seaborn

### 3️⃣ Download Dataset

Download the 2015 US Flights dataset and place the following files in the project folder:

- flights.csv
- airlines.csv
- airports.csv

⚠️ Make sure `flights.csv` is in the same folder as the notebook.

### 4️⃣ Run the Notebook

Open:

Airline_Delay_Root_Cause_Analysis.ipynb

Then run all cells.

If the dataset is missing, the notebook will raise a clear error message.

