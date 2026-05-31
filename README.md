# 🏥 Medical Appointment No-Show Analysis

COLAB LINK - https://colab.research.google.com/drive/1ol7HQvLFadRRQ0ZxaYMWvKpQA90ePp06#scrollTo=-pwiQNGOb5on

A data analytics project that investigates the factors influencing whether patients attend or miss their scheduled medical appointments. Using a real-world healthcare dataset, this project demonstrates the complete data analysis workflow, including data cleaning, feature engineering, exploratory data analysis (EDA), and data visualization.

## 📌 Project Overview

Missed medical appointments can negatively impact healthcare providers and patient outcomes. This project analyzes appointment records to identify patterns associated with patient attendance and no-show behavior.

The analysis explores the impact of factors such as:

* Age
* Gender
* SMS reminders
* Waiting time before appointments
* Medical conditions (Hypertension, Diabetes, Alcoholism, Handicap)
* Scholarship status
* Appointment scheduling patterns

## 🚀 Open in Google Colab

Open and run the notebook directly in Google Colab:

https://colab.research.google.com/drive/1ol7HQvLFadRRQ0ZxaYMWvKpQA90ePp06

---

## 📂 Project Structure

```text
medical-noshow-analysis/
├── data/
│   ├── raw/
│   │   └── medical_noshow.csv
│   └── cleaned/
│       ├── medical_noshow_cleaned.csv
│       └── medical_noshow_features.csv
├── charts/
│   ├── age_distribution.png
│   ├── attendance_pie.png
│   ├── correlation_heatmap.png
│   ├── noshow_by_age_group.png
│   ├── noshow_by_day.png
│   ├── noshow_by_gender.png
│   ├── noshow_by_sms.png
│   └── waitingdays_boxplot.png
├── medical_noshow_analysis.py
└── README.md
```

## 📊 Dataset Information

The dataset contains medical appointment records with demographic, scheduling, and health-related information.

### Key Features

| Column         | Description                                         |
| -------------- | --------------------------------------------------- |
| Age            | Patient age in years                                |
| Gender         | Patient gender (M/F)                                |
| ScheduledDay   | Date the appointment was booked                     |
| AppointmentDay | Date of the appointment                             |
| Scholarship    | Welfare program participation (0/1)                 |
| Hypertension   | Hypertension diagnosis (0/1)                        |
| Diabetes       | Diabetes diagnosis (0/1)                            |
| Alcoholism     | Alcoholism diagnosis (0/1)                          |
| Handicap       | Disability status (0/1)                             |
| SMS_received   | Whether an SMS reminder was sent (0/1)              |
| No-show        | Whether the patient missed the appointment (Yes/No) |

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

---

## 📈 Analysis Performed

### Data Cleaning

* Removed inconsistencies and missing values
* Standardized column names
* Converted date columns to datetime format

### Feature Engineering

* Created waiting-time features
* Derived appointment day information
* Generated age-group categories

### Exploratory Data Analysis (EDA)

* Age distribution analysis
* Gender-wise attendance trends
* Impact of SMS reminders
* Day-of-week attendance patterns
* Waiting-time analysis
* Correlation analysis

### Data Visualization

The project includes multiple visualizations:

* Age Distribution
* Attendance Pie Chart
* No-Show by Gender
* No-Show by SMS Reminder
* No-Show by Age Group
* No-Show by Appointment Day
* Waiting Days Boxplot
* Correlation Heatmap

---

## 💡 Key Insights

* Appointment attendance varies across age groups.
* Waiting time before appointments influences no-show rates.
* SMS reminders alone may not guarantee attendance.
* Certain appointment days exhibit higher no-show frequencies.
* Demographic and medical factors contribute to attendance behavior.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/likhithaj21/medical-noshow-analysis.git
cd medical-noshow-analysis
```

Install required packages:

```bash
pip install pandas matplotlib seaborn
```

Run the analysis:

```bash
python medical_noshow_analysis.py
```

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Healthcare Data Analytics
* Python Data Science Libraries

---

GitHub: https://github.com/likhithaj21
