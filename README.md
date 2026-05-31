# Medical Appointment No-Show Analysis
colab link - https://colab.research.google.com/drive/1ol7HQvLFadRRQ0ZxaYMWvKpQA90ePp06#scrollTo=-pwiQNGOb5on
A data analysis project that explores patterns in medical appointment attendance using a real-world dataset. The project covers end-to-end data processing — from raw CSV ingestion through cleaning, feature engineering, and visualisation — to uncover factors that influence whether patients show up for their appointments.

Project Structure
medical-noshow-analysis/
├── data/
│   ├── raw/
│   │   └── medical_noshow.csv          # Original dataset
│   └── cleaned/
│       ├── medical_noshow_cleaned.csv  # After cleaning
│       └── medical_noshow_features.csv # After feature engineering
├── charts/
│   ├── age_distribution.png
│   ├── noshow_by_gender.png
│   ├── noshow_by_sms.png
│   ├── correlation_heatmap.png
│   ├── noshow_by_age_group.png
│   ├── attendance_pie.png
│   ├── waitingdays_boxplot.png
│   └── noshow_by_day.png
├── medical_noshow_analysis.py          # Main analysis script
└── README.md

Dataset
The dataset contains medical appointment records with the following key columns:
ColumnDescriptionagePatient age in yearsgenderPatient gender (M/F)scheduleddayDate the appointment was bookedappointmentdayDate of the actual appointmentscholarshipWhether the patient is on a welfare programme (0/1)hypertensionHypertension diagnosis (0/1)diabetesDiabetes diagnosis (0/1)alcoholismAlcoholism diagnosis (0/1)handicapDisability status (0/1)sms_receivedWhether an SMS reminder was sent (0/1)no_showWhether the patient missed the appointment (Yes/No)

Requirements
pandas
matplotlib
seaborn
Install with:
bashpip install pandas matplotlib seaborn
