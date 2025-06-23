# Investigate the Relationship Between SMS Reminders and Appointment Attendance

This project analyzes over 110,000 medical appointments in Brazil to explore the factors that influence whether a patient shows up for their scheduled appointment. The focus is on identifying trends and relationships in the data that can help reduce no-shows and improve healthcare delivery.

## Project Overview

Missed medical appointments ("no-shows") cause significant inefficiencies in healthcare systems. By analyzing this dataset from Kaggle, we aim to understand what patient or appointment attributes predict whether a person shows up.

### Main Question
**What factors are most influential in predicting if a patient will miss their appointment?**

## Dataset

The dataset includes 110,527 appointment records from various neighborhoods in Brazil. Key columns:
- `PatientId`, `AppointmentID`, `Gender`
- `ScheduledDay`, `AppointmentDay`, `Age`
- `Neighbourhood`, `Scholarship`, `Hipertension`, `Diabetes`
- `Alcoholism`, `Handcap`, `SMS_received`
- `No-show` (target variable)

## Tools Used

- Python (Google Colab)
- pandas, numpy, matplotlib

## Data Cleaning Steps

- Renamed inconsistent column names
- Converted date strings to datetime objects
- Removed duplicates
- Handled invalid age entries (e.g., negative values)

## Key Insights

- Factors such as age, SMS reminders, and scholarship status showed correlation with no-show rates.
- Timing between scheduling and appointment date may also influence attendance.

## Files Included

- `Investigate_a_Dataset.ipynb` – The full analysis notebook
- `Medical_Appointment_No_Shows.csv` – Dataset used in the project

## Author

Felwah Alarifi – Data Science Master's Student  
