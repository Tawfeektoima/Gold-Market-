# Gold Price Analysis: Egypt vs USA (1979–2023)

## Overview
This project investigates gold price trends across multiple countries from **1979 to 2023**. The main focus is on **Egypt** and the **United States**, aiming to understand:

- The **seasonality of buying and selling gold in Egypt**
- The **correlation between the Egyptian and U.S. gold markets**

To ensure accurate comparison, we removed all other countries from the original dataset and included an additional dataset for the **EGP to USD exchange rate**. This allowed us to normalize Egyptian gold prices to USD values.

---

## Key Findings

- A **strong correlation** was observed between gold prices in Egypt and the United States.
- Major global events had clear impacts on both markets:
  - **9/11 Attacks (2001)**
  - **Global Financial Crisis (2008)**
  - **Oil oversupply in 2015** during U.S.–Russia competition
  -  **COVID-19 Pandemic (2020)**
- U.S. gold prices were consistently **slightly higher** than in Egypt after conversion, though both markets followed **very similar trends**.

- <img width="633" height="382" alt="image" src="https://github.com/user-attachments/assets/35c6a708-71e7-4b41-b955-7a0e25cd3f33" />


---

##  Seasonal & Monthly Trends (Egypt)

- **Quarterly patterns**:
  -  **High buying activity in Q1** (Jan–Mar) → price increases
  -  **Increased selling in Q3** (Jul–Sep) → price decreases
  -  <img width="836" height="388" alt="image" src="https://github.com/user-attachments/assets/ae7f1af2-50ea-42cc-bee3-0f4a8c5498b9" />


- **Monthly behavior**:
  - 🛍 At the **start of each month**, buying activity tends to rise, pushing prices up.
  -  At the **end of each month**, selling increases, leading to price declines.

---<img width="765" height="341" alt="image" src="https://github.com/user-attachments/assets/49167d05-f2e0-4138-a831-6b93b8b6fb3e" />


##  Data Sources

- Historical gold prices dataset (1979–2023) across multiple countries
- USD/EGP exchange rate dataset (for currency conversion)

---

##  Conclusion

The results confirm a **strong linkage** between Egypt’s gold market and the U.S. gold market. Despite differences in local economics and currency, **Egyptian gold prices closely mirror U.S. price trends**. This project also identifies clear **seasonal cycles** in gold buying and selling behaviors within Egypt, which could be valuable for investors and analysts.

---

## Future Work

- Use time series models (ARIMA, LSTM) to forecast future prices
- Extend comparison to include other regional gold markets
- Analyze the impact of local economic policies in Egypt on gold prices
