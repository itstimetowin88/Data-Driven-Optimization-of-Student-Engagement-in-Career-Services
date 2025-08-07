# XM Qualtrics Engineering Survey Design: Boosting Internship Survey Engagement through Behavioral Insights

## 📘 Project Overview

This project applies marketing research principles and behavioral data analytics to understand and optimize how undergraduate students at the University of Maryland's Robert H. Smith School of Business respond to internship and placement surveys. Using a well-structured Qualtrics survey, we explore how factors such as communication preferences, incentives, and exposure to career services influence survey engagement.

---

## 🎯 Problem Statement

The Office of Career Services (OCS) at UMD faces low response rates for surveys used to collect internship and job placement data. This limits their ability to:
- Track student employment outcomes
- Provide targeted support
- Improve reporting accuracy

**Objective:**  
Design and analyze a survey to identify which levers (student characteristics, exposure, incentives) most influence completion rates of OCS internship surveys.

---

## 📊 Dataset

The dataset was collected using **Qualtrics XM**, with 12 primary questions grouped into:

- 🎓 Student Characteristics  
  e.g., year, major, employment status  
- 🏢 OCS Exposure  
  e.g., received survey, completed survey, communication method  
- 🎁 Rewards & Incentives  
  e.g., Likert-scale likelihood to respond with/without prizes, and prize preference

**Response Sample:**  
- ~3 responses from pilot data  
- All responses filtered to include only current UMD Smith undergraduate students

---

## 🔑 Key Features

### ✔ Student Profile Fields
- Academic Year
- Business Major(s)
- Employment Status

### ✔ Behavioral Insights
- Likelihood to complete survey **with** vs. **without** a raffle prize
- Constant sum allocation of 10 points across prize types:
  - Career Coaching
  - UMD Swag
  - LinkedIn Premium
  - Coffee Chat with Alumni

### ✔ Communication Preferences
- Preferred method: Email, SMS, Canvas, etc.
- Past receipt and completion of OCS survey

---

## 🧠 Methodology

### 1. **Survey Design**
- Online-only survey using **Qualtrics**
- Screener → Student Characteristics → Exposure → Motivation
- Logical flow minimizes fatigue and maximizes response quality

### 2. **Distribution Channels**
- Email blast to Smith undergrads
- Student org outreach (clubs, ambassadors)
- Classroom announcements
- Social platforms (TerpLink, LinkedIn)

### 3. **Data Handling**
- Cleaned raw CSV export (removed metadata rows)
- Mapped variables using Import IDs (e.g., `QID14` = Likelihood without prize)

---

## 📈 Planned Analysis

- **Cross-tabulation**: completion vs. year, major, exposure
- **Likert scale comparison**: prize impact on motivation
- **Constant sum analysis**: rank prize effectiveness
- **Chi-square tests / Logistic regression** (if extended)

---

## 📁 Repository Structure

