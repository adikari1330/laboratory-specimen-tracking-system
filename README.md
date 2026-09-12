Laboratory Specimen Registration & Tracking System — Clinical Cohort Analysis (Victoria)

This project demonstrates how a clinical cohort dataset can be used to simulate a Laboratory Specimen Registration & Tracking System. The dataset contains specimen collection dates, patient outcomes, cancer staging, and survival time. All analysis is performed in Google Colab using Python, Pandas, Seaborn, and Matplotlib.

📁 Project Overview
The goal of this project is to analyse a real clinical-style cohort dataset and model how specimen metadata can be used in a laboratory tracking workflow. The project includes data cleaning, date conversion, exploratory analysis, and visualisations to understand clinical patterns and specimen timelines.

📊 Dataset Description
The dataset contains 30 patient records, each representing a specimen collected for diagnostic or research purposes.

Columns included:

PatientID

Specimen date

Dead or Alive

Date of Death

Date of Last Follow Up

sex

race

Stage

Event

Time

This dataset is suitable for clinical data analysis, specimen tracking simulation, survival analysis, stage-based comparison, and visualisation practice.

🔧 Technologies Used
Python 3
Google Colab
Pandas
NumPy
Matplotlib
Seaborn

🧼 Data Cleaning & Preparation
The dataset required several preprocessing steps to ensure accurate analysis:

Missing values (represented as ".") were cleaned and converted to proper null values.
Date fields contained mixed formats and extra spaces, so they were stripped and safely converted into datetime objects.
All fields were validated to ensure consistency before visualisation.

📈 Visualisations
This project includes multiple visualisations to understand clinical patterns and specimen behaviour.

1. Stage Distribution
A bar chart showing how many patients fall into each cancer stage.
This helps identify which tumour stages are most common in the cohort.


3. Survival Status (Dead vs Alive)
A count plot showing the number of patients who survived versus those who did not.
Useful for understanding overall cohort outcomes.

4. Time-to-Event Distribution
A histogram showing the distribution of survival time (in days).
This highlights how long patients lived after specimen collection.

5. Specimen Collection Timeline
A line plot showing how specimen collection dates are distributed over time.
This visualises specimen flow and collection frequency.

6. Survival Time by Stage (Boxplot)
A boxplot comparing survival time across tumour stages.
This helps identify whether certain stages correlate with shorter or longer survival.

7. Sex Distribution
A simple bar chart showing male vs female distribution.

8. Race Distribution
A bar chart showing racial distribution within the cohort.

All visualisations were generated in Google Colab using Matplotlib and Seaborn.

🧪 Specimen Tracking Simulation
Although the dataset is clinical, it is used to simulate:
Specimen registration
Specimen timeline tracking
Outcome monitoring
Stage-based specimen grouping
Time-based specimen analysis

This aligns with real laboratory workflows used in Victoria.

🚀 How to Run This Project
1. Open Google Colab
Upload the notebook and dataset.

2. Install dependencies
Install Pandas, Seaborn, and Matplotlib.

3. Run the notebook
All visualisations will be generated automatically.

🔮 Future Improvements
Add Stage 0 specimens
Integrate Kaplan–Meier survival curves
Build a specimen tracking dashboard
Add machine learning predictions
Connect to a mock LIMS (Laboratory Information Management System)

📬 Author
Shashi Adikari
