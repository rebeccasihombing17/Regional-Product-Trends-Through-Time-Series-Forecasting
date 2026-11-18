# 📈 Regional Product Trends Through Time Series Forecasting

> Turning transaction history into smarter, region-specific marketing decisions with **Auto-ARIMA**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Auto-ARIMA](https://img.shields.io/badge/Model-Auto--ARIMA-orange?style=flat)
![Looker Studio](https://img.shields.io/badge/Dashboard-Looker_Studio-4285F4?style=flat&logo=looker&logoColor=white)
![MBKM](https://img.shields.io/badge/Project-MBKM-green?style=flat)

---

## 🎯 Overview

This repository contains the artefacts of my **MBKM project in Data Science & AI**. The project forecasts product purchase trends across regions using time series analysis, so businesses can anticipate demand instead of just reacting to it.

## 💡 Business Problem

Consumer behavior changes fast. A product that sells well in one region may stall in another, and marketing teams that rely on past reports often react too late.

The key questions:
- Which products will grow or decline in each region?
- Where should marketing effort be focused next?
- When should existing products be adjusted?

## 🛠️ Solution

I built a forecasting pipeline using **Auto-ARIMA** that:

1. Aggregates transaction data by product and region over time
2. Automatically selects the best ARIMA parameters for each series
3. Predicts future purchase quantities per product per region
4. Presents the results in an interactive dashboard for decision-makers

The outcome is a data-driven basis for **region-specific marketing strategies**.

## 📊 Interactive Dashboard

Explore the forecasting results directly:

[![Looker Studio Dashboard](https://img.shields.io/badge/Looker_Studio-View_Dashboard-4285F4?style=for-the-badge&logo=looker&logoColor=white)](https://datastudio.google.com/reporting/700c9a34-6d5f-4f21-8967-1fad4b3ab7c1)

[![Dashboard Preview]()](https://datastudio.google.com/reporting/8e862eb0-41f7-47c3-bcff-d2aa86492ab9)

*Click the image to open the live dashboard.*

## 🗂️ Dataset

The analysis uses **`maintrx`**, a transaction dataset. Its attributes are shown below:

<img width="714" height="329" alt="maintrx dataset attributes" src="https://github.com/user-attachments/assets/8914b392-2ef1-4aed-b0eb-68455024ac26" />
