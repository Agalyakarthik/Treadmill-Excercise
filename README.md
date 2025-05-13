# Treadmill-Excercise
Treadmill Exercise Cardiorespiratory Dataset Analysis
This repository contains analysis tools and scripts for working with the "Treadmill Exercise Cardiorespiratory Measurements" dataset from PhysioNet.
Dataset Description
The dataset contains cardiorespiratory measurements from 37 subjects (19 male, 18 female) performing a treadmill exercise test. The data was collected at the Cardiovascular Performance Laboratory of Brigham and Women's Hospital, Boston, MA. Each subject performed a symptom-limited treadmill exercise test following the standard Bruce Protocol, which involves increases in treadmill speed and elevation every 3 minutes.
Key Features

Breath-by-breath measurements of oxygen uptake (VO2), carbon dioxide production (VCO2), ventilation (VE), and other cardiorespiratory variables
Heart rate and ECG measurements
Treadmill speed and grade data
Subject demographic information (age, gender, height, weight)
Measurements during both exercise and recovery phases

Dataset Structure
The dataset includes:

Subject demographic data (demographics.csv) - Contains information about participants including age, gender, height, weight, and BMI
Exercise data files - Individual .csv files containing breath-by-breath data for each subject
Documentation - Detailed information about data collection protocol and variable definitions

Main Variables

VO2: Oxygen uptake (mL/min) - A key indicator of aerobic capacity
VCO2: Carbon dioxide production (mL/min)
VE: Minute ventilation (L/min)
HR: Heart rate (beats/min)
RER: Respiratory exchange ratio (VCO2/VO2)
VO2/kg: Oxygen uptake normalized for body weight (mL/min/kg)
Treadmill speed and grade: Exercise intensity parameters

Getting Started
Prerequisites
python 3.8+
pandas
numpy
matplotlib
seaborn
scipy

Dataset[https://physionet.org/content/treadmill-exercise-cardioresp/1.0.1/]
