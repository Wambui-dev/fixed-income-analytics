# Fixed Income & Bond Analytics Toolkit

A Python-based toolkit developed during my 2nd year of Financial Engineering to automate bond pricing, yield calculations, and risk metrics.

## 📊 Features Implemented
* **Bond Pricing:** Solves for present value given coupon rate, face value, and YTM.
* **Yield to Maturity (YTM):** Uses numerical methods to back out YTM from market prices.
* **Risk Metrics:** Calculates Macaulay Duration, Modified Duration, and Convexity.

## 🧮 Mathematical Formulas Used
* *Bond Price:* P = sum( C / (1+y)^t ) + M / (1+y)^n
* *Macaulay Duration:* D = [ sum( t * C / (1+y)^t ) ] / P

## 🚀 How to Run
1. Clone the repo: git clone https://github.com
2. Run the main analytical script: python bond_calculator.py
