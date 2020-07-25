# Investigate a Dataset

## Introduction
In this project I took the following steps:
- Chose my dataset
- Wrote Python code for wrangling and analysis
 - I used Python to assess and clean the data, and also to analyse the data.
- Reported my findings

I chose the no show medical appointments. This dataset collects information from 110,527 medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. Fourteen characteristics about the patient are included in each row. The dataset can be accessed on [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments).

## About the project
I found that I wanted to:
- Change PatientId column format to integer
- Change the headings into snake case and also shorten their names
- Change ScheduledDay and AppointmentDay columns to a date format
- Crop the -1 year old age patient
- Drop Handcap
- Change no-show to a dummy variable
- Calculate the difference between ScheduledDay and AppointmentDay.

The questions I planned on answering were:
- What proportion of people do not show up to their appointments?
- Are different genders more likely to show to their appointments?
- Are different variables more likely to show to their appointments?
- Are people more likely to show if they receive a text?
- What is the average difference between scheduled and appointment day? How does this affect appointment attendance?

To find out my conclusions, you can click [here]() to be taken to my Jupyter notebook.
