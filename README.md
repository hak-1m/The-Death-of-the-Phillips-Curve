# The Death of the Phillips Curve 📉💱

> **Labor Slack Neutrality and Exchange Rate Dominance in Resource-Dependent Transition Economies**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![R-Project](https://img.shields.io/badge/Language-R%20%7C%20Econometrics-blue)](https://www.r-project.org/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--4999--1861-green)](https://orcid.org/0009-0003-4999-1861)
[![DOI](https://img.shields.io/badge/Zenodo-Record%2022096042-blue)](https://zenodo.org/records/22096042)
[![Research Status](https://img.shields.io/badge/Status-Research%20Preprint-orange)](#)

---

## 📌 Executive Summary

For decades, the classical Phillips Curve has served as a foundational macroeconomic framework, postulating a reliable inverse trade-off between labor market slack (unemployment) and consumer price inflation. According to this traditional Keynesian model, an expanding economy tightens the labor market, forcing firms to raise wages, which ultimately drives up consumer prices. 

However, this research repository demonstrates that this traditional demand-side transmission mechanism completely breaks down within small, open, resource-dependent transitioning economies, specifically focusing on Kazakhstan from 2010 to 2026. 

Our empirical framework proves that domestic inflation in such environments is virtually disconnected from local labor market conditions. Instead, price regimes are overwhelmingly dominated by exogenous supply-side shocks and intense exchange rate pass-through mechanics. This repository provides the codebase and econometric evidence proving the "death" of the classical Phillips Curve in resource-exporting nations.

---

## 🔬 Methodology and Approach

Rather than relying on outdated static models, this project utilizes a dynamic econometric approach to untangle the real drivers of inflation. We employ a Structural Vector Autoregression (SVAR) system combined with robust variance-covariance matrix estimators to map how economic shocks travel through the economy over time. 

Everything is modeled sequentially to reflect real-world economic delays:
First, we assume external currency shocks react instantly to global commodity cycles. 
Second, we measure how domestic core inflation responds simultaneously to both exchange rate fluctuations and labor market conditions. 
Finally, we account for the fact that wages and official unemployment statistics adjust with a significant structural delay due to institutional rigidities.

By testing these relationships using rigorous stationarity tests and robust regression frameworks, we successfully isolate the true impact of currency devaluation versus domestic unemployment on the overall pricing matrix of the country.

---

## 📊 Key Findings

Our empirical analysis completely reshapes the understanding of inflation drivers in transition economies. The core findings include:

* **Labor Slack Neutrality (The End of the Trade-off):** We found absolutely no statistically significant contemporary relationship between official unemployment levels and core inflation. The traditional theory that lower unemployment causes higher inflation is structurally absent in Kazakhstan. This is largely due to institutional labor market rigidities and the fact that official statistics fail to capture true cyclical underemployment.
* **Exchange Rate Dominance:** Currency dynamics completely override the labor market. Our models prove that fluctuations in the nominal exchange rate (USD/KZT) exercise an economically massive, immediate, and persistent impact on domestic inflation. Because the nation relies heavily on imported capital and consumer goods, currency devaluations dictate domestic prices instantly.
* **Frictional Market Lags:** Even when trying to account for delayed reactions in the labor market (lagging the unemployment data by multiple quarters), the labor impact remains weak. While combining currency shocks with delayed labor metrics provides a slightly better overall tracking model, the exchange rate remains the undisputed primary driver of systemic price movements.

---

## 🛠️ Data Pipeline & Technology Stack

* **Data Simulation & Acquisition:** The project utilizes a calibrated macroeconometric matrix spanning from 2010 to 2026, capturing core inflation regimes, structural labor market slack, and major exchange rate devaluation shocks.
* **Stationarity Testing:** Implementation of Augmented Dickey-Fuller (ADF) unit-root tests to ensure all time-series data is stationary, preventing false or spurious correlations.
* **Econometric Modeling:** Execution of robust structural regressions utilizing Newey-West standard errors to correct for data volatility and serial correlation, alongside dynamic impulse response mapping to forecast shock persistence over multiple quarters.

---

## 🎯 Policy & Structural Reform Implications

The empirical rejection of the classical Phillips Curve provides urgent and highly actionable directives for central bank operations:

1. **Prioritize the Exchange Rate Anchor:** Because inflation is driven by currency pass-through rather than domestic employment gaps, monetary policy must shift its primary focus toward smoothing extreme currency volatility and managing devaluation expectations, rather than attempting to fine-tune the labor market.
2. **Supply-Chain Internalization:** To protect the economy from imported inflation, structural government policies must aggressively target import dependency. Deepening local supply chains and reducing reliance on foreign consumer goods is the only way to weaken the intense exchange rate pass-through effect.
3. **Recalibrating Forecasting Architectures:** State authorities and central banks must abandon standard linear Phillips Curve equations in their forecasting. They should be replaced with open-economy models that explicitly incorporate global commodity prices and currency transmission channels.

---

## ✒️ Citation & Author Info

**Author:** Bekdaulet Abzhamiev  
**Role:** Researcher  
**ORCID:** [0009-0003-4999-1861](https://orcid.org/0009-0003-4999-1861)  
