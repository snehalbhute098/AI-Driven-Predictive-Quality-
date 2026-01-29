# AI-Driven Predictive Quality System for Cold Chain Management

## Overview

This project focuses on reducing post-harvest food losses in India by transforming traditional cold storage into intelligent warehousing using Machine Learning and IoT sensor data.

Instead of reacting after spoilage occurs, this system predicts quality degradation in advance by generating a Spoilage Risk Score (0–100%), enabling proactive logistics and waste reduction.

The solution integrates environmental data such as Temperature, Humidity, CO₂, and Light to detect early biological signals of decay across multiple commodities.

---

## Problem Statement

India loses nearly ₹1 lakh crore annually due to post-harvest inefficiencies. Existing cold-chain systems are reactive and only alert when failures happen.

This project introduces a predictive approach that identifies biological decay before fruits visibly spoil, helping stakeholders take early corrective actions.

---

## Key Features

- Predictive Spoilage Risk Score (0–100%)
- Multi-commodity support (Banana, Orange, Pineapple, Tomato)
- Root Cause Analysis (identifies main drivers like Humidity or CO₂)
- Sensor Anomaly Detection
- Explainable AI using Decision Trees
- Cross-validated high model stability

---

## Methodology

The system follows a structured ML pipeline:

1. Data Integration from IoT sensors (Temperature, Humidity, CO₂, Light)
2. Exploratory Data Analysis to identify spoilage patterns
3. Feature Standardization to balance sensor influence
4. Training a Random Forest Classifier as a universal model
5. Validation using 5-Fold Cross Validation

A single model learns different biological behaviors of fruits using Fruit_ID encoding, automatically creating specialized decision paths for fragile and hardy commodities.

---

## Major Findings

- Humidity is the primary gatekeeper of quality.
- CO₂ acts as an early indicator of spoilage.
- Light shows correlation with temperature, suggesting warehouse lighting contributes to heat stress.
- Environmental mismanagement affects all fruits more than fruit type itself.

Model achieved approximately 97.43% stability with near-zero dangerous misclassifications.

---

## Industry Enhancements

- Spoilage Risk Probability instead of binary output
- FEFO (First Expired First Out) logistics support
- Root cause alerts for operational decisions
- Sensor health monitoring

---

## Policy & Practical Impact

- Early diversion of at-risk produce
- Reduced food waste
- Improved cold-chain transparency
- Data-driven infrastructure planning
- Scalable design for adding new commodities

This model acts as a “Biological Passport” for food shipments.

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Random Forest Classifier  
- Exploratory Data Analysis  
- Decision Trees  
- Cross Validation  

---

## Future Scope

- Add more commodities (e.g., Mango)
- Real-time dashboard integration
- Deployment with live IoT feeds
- Integration with logistics systems

---

## Author

Snehal Bhute

