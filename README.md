# The Pilots: Delay Decoder

**STAT 167 - Introduction to Data Science Final Project**  
Authors: Sophia Chavez, Elif Turgut, Joseph Nam, Justin Henriquez, Arjun Sharma, Lance Santana  
Date: June 8, 2025

---

## Project Overview

Each year, millions of travelers experience flight delays. Our goal was to identify patterns and predictors of delays using data from the top 10 busiest U.S. airports. We analyzed variables such as weather, flight time, aircraft, airline carrier, and airport of origin to help passengers make more informed booking decisions.

This project uses the `anyflights` and `nycflights13` datasets to answer the question:  
**What conditions most strongly predict delayed flights in the U.S.?**

---

## Key Findings

- **Time of Day**: Early morning flights have fewer delays.
- **Month**: January–May and September–November have lower delay rates.
- **Weather**: High wind gusts significantly increase delay probability.
- **Aircraft Age**: Newer planes tend to experience fewer delays.
- **Airports**: DEN, DFW, LAS, and ORD are more prone to delays.
- **Airlines**:
  - **Least Delays**: Alaska (AS), Delta (DL), US Airways (US)
  - **Most Delays**: Southwest (WN), Frontier (F9), ExpressJet (EV)

---

## Methods Used

- Exploratory Data Analysis (EDA)
- Linear and Logistic Regression
- One-way and Two-way ANOVA
- Data visualization using `ggplot2`
- Data manipulation using `dplyr` and `tidyverse`

---

## Dataset

- [anyflights](https://github.com/simonpcouch/anyflights): Real-time flight data from U.S. airports  
- [nycflights13](https://cran.r-project.org/web/packages/nycflights13/index.html): 2013 flight data from NYC airports

We used flights from 2013 departing from these airports: ATL, LAX, DFW, DEN, ORD, MCO, JFK, LAS, CLT, MIA.

---

## Technologies

- R  
- RMarkdown  
- Packages: `anyflights`, `nycflights13`, `ggplot2`, `dplyr`, `lubridate`, `patchwork`, `agricolae`

---

## Limitations

- Focused only on the top 10 busiest U.S. airports
- Real-time data retrieval from `anyflights` caused slowdowns
- Limited granularity—more detailed temporal or spatial analysis could provide deeper insights

---

## Team Contributions

- **Sophia Chavez** – Month, distance, and weather analysis; report setup  
- **Elif Turgut** – Weather visuals, time of day analysis  
- **Joseph Nam** – Objective framing, time of day, plane age analysis  
- **Justin Henriquez** – Background and objectives  
- **Arjun Sharma** – Carrier and origin analysis  
- **Lance Santana** – Flight quantity vs. delay analysis, final presentation slides

---

## License

This project is licensed under the [MIT License](LICENSE).
