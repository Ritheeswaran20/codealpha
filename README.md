# CodeAlpha Project: Exploratory Data Analysis (EDA) and Data Visualization
Internship tasks covered: Task 2 (EDA) and Task 3 (Data Visualization)

Project overview
This beginner-friendly project analyses a small sample sales dataset with Python, Pandas, and Matplotlib. It checks the dataset structure, data types, missing values, duplicate rows, summary statistics, revenue by product and region, monthly revenue, and units sold by category. It saves charts and a short findings report.

The CSV is a sample dataset created for learning. It is not real company data.

Project structure
CodeAlpha_EDA_Data_Visualization/
├── analysis.py
├── requirements.txt
├── README.md
├── data/
│   └── sales_data.csv
└── outputs/
    └── (created when you run the script)
Step 1: Install Python
If Python is not installed, install Python 3 from https://www.python.org/downloads/ . On Windows, select Add Python to PATH during installation if the option appears.

Step 2: Open the project folder
Extract the project ZIP. Open the extracted CodeAlpha_EDA_Data_Visualization folder. In File Explorer, click the address bar, type cmd, and press Enter to open Command Prompt in that folder.

Step 3: Install the required libraries
Run:

python -m pip install -r requirements.txt
If python is not recognised, try py -m pip install -r requirements.txt.

Step 4: Run the project
Run:

python analysis.py
Or, if needed:

py analysis.py
Step 5: Check your results
The program creates an outputs folder containing:

revenue_by_product.png — bar chart
monthly_revenue.png — line chart
units_by_category.png — pie chart
order_revenue_histogram.png — histogram
revenue_by_product.csv, revenue_by_region.csv, monthly_revenue.csv — summary tables
insights_report.txt — key findings
What the analysis does
Loads the CSV file.
Checks rows, columns, data types, missing values, and duplicates.
Calculates descriptive statistics.
Calculates revenue as UnitsSold × UnitPrice.
Answers questions such as:
Which product generated the highest revenue?
Which region generated the highest revenue?
Which month had the highest revenue?
Which category sold the most units?
Creates charts and saves a report.
GitHub upload checklist
Sign in to GitHub and create a new public repository named CodeAlpha_EDA_Data_Visualization (the internship instructions ask for the format CodeAlpha_ProjectName).
Upload analysis.py, requirements.txt, README.md, and the data folder with sales_data.csv.
Run the project locally first and optionally upload the generated outputs folder too.
Add a short repository description, such as: Beginner sales data analysis using Python, Pandas, and Matplotlib.
Do not upload passwords, private information, or confidential company data.
