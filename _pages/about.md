---
permalink: /
title: "Hello there, I'm Somak!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



👨🏻‍💻 I'm a final year undergraduate student at the SRM Institute of Science and Technology, Kattankulathur, studying Electronics and Computer Engineering.

🔬 My research interest is in integrating signal processing to solve biomedical problems!

📚 I'm currently working towards my Bachelor's Thesis in the field of Biomedical Radar Sensing at Indian Institute of Technology, Kharagpur

# ⭐ Bachelor Thesis 
## Project Overview:
This project analyzes respiratory patterns in normal and COPD patients using radar signal processing to detect differences under conditions like resting, walking, running, and climbing stairs.

## Objective:
The goal is to derive respiratory rates, evaluate signal-to-noise ratios (SNR), and create a framework for early detection and monitoring of respiratory diseases.

## Data Processing Approach:
Radar data is preprocessed using Python with bandpass and Savitzky-Golay filters for noise reduction. Key metrics, such as respiratory rate, are extracted using peak detection within a realistic range of 12-18 BPM.

## Hardware and Software Used:

Hardware: IWR1843 radar kit, DCA1000EVM, Empatica E4.

Software: Python (NumPy, SciPy, Matplotlib) on Google Colab.
          Custom-made Python packages that ensure efficient processing of large binary files containing doppler values (Repo link will be added later!)

## Key Findings:
[Preliminary results](https://drive.google.com/file/d/1G6Jy-EOB2NYpfBtVolBYQ0lGKT9mMzh5/view) reveal distinct respiratory patterns for COPD patients compared to normal subjects. Heatmaps and range profiles validate these insights.

## Challenges and Continuing Work:
Managing large binary datasets and optimizing real-time signal processing remain challenging. Work is ongoing to improve SNR calculations and refine respiratory rate accuracy.

The subsequent conference paper is submitted to IEEE PerCom 2025 Work-in-Progress (WiP) session.

# ⭐ Final Year Project
## Project Overview:

This project aims to develop an innovative tool for early detection of fetal distress by monitoring both uterine contractions and fetal heart rate (HR). The system will alert healthcare providers and pregnant mothers in real-time to ensure timely intervention, significantly improving the chances of saving the baby. This solution will be paired with a hardware system, which will be patented, providing a comprehensive approach to fetal monitoring.

## Objective:

The goal of the project is to design a hardware system that detects early signs of fetal distress by continuously monitoring uterine contractions and fetal HR. The system will trigger an alarm to alert the pregnant mother and healthcare providers, enabling swift action. The project’s focus is on ensuring the safety of the fetus through proactive monitoring during critical periods of labor.

## Data Processing Approach:

The project will employ a combination of hardware-based sensing and software processing:

Data Sensing: Uterine contractions and fetal heart rate are monitored using non-invasive sensors.
Data Processing: Signal processing algorithms are applied to the collected data to detect early signs of fetal distress.
Real-time Monitoring: The system processes the data continuously, with the alert system triggering based on pre-defined thresholds for uterine contractions and fetal HR.

## Hardware and Software Used:

Hardware:

Custom-built monitoring system to measure uterine contractions and fetal heart rate.
Wearable sensors for real-time data collection from the mother and fetus.
A microcontroller for real-time data processing and alarm triggering.
The system will be patented to ensure exclusivity in the market.

Software:

Python (for data processing and algorithm development).
TensorFlow (for machine learning-based pattern recognition).
SciPy and Matplotlib (for data analysis and visualization).

## Key Findings:

Preliminary studies suggest that the combination of uterine contraction monitoring with fetal HR provides a reliable way to predict fetal distress. This system shows the potential for significantly reducing adverse outcomes by providing earlier warnings. Early tests show promising results in identifying patterns that could lead to fetal hypoxia or other complications.

## Challenges and Continuing Work:

Challenges: Ensuring accurate real-time detection of uterine contractions and fetal HR in varying conditions.
Ongoing Work: Optimization of the hardware for portability and comfort, as well as refining the machine learning algorithms for higher prediction accuracy.

The project’s paper is in progress for submission to Nature Biomedical Engineering, showcasing the potential impact of this system on improving fetal health outcomes.
