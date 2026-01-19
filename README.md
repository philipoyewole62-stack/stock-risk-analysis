# stock-risk-analysis
Historical VaR analysis using Python and pandas
📊 Project Title

Historical Value at Risk (VaR) Analysis of JPMorgan and NVIDIA Stocks

⸻

🧠 Project Overview

This project analyzes the daily risk of two stocks — JPMorgan Chase (JPM) and NVIDIA (NVDA) — using one year of historical price data.
The goal is to identify potential losses by applying historical simulation and Value at Risk (VaR) techniques.

⸻

📁 Data Description
	•	One year of daily closing prices
	•	Stocks analyzed:
	•	JPMorgan Chase (JPM)
	•	NVIDIA (NVDA)

⸻

🛠 Tools & Libraries Used
	•	Python
	•	pandas – data cleaning and return calculation
	•	NumPy – percentile-based risk estimation
	•	matplotlib – risk visualization

⸻

🔍 Methodology (explained)
	1.	Converted daily prices into daily percentage returns
	2.	Ranked historical returns from worst to best (historical simulation)
	3.	Estimated 5% Value at Risk (VaR) to measure downside risk
	4.	Combined both stocks into a 50/50 portfolio
	5.	Calculated portfolio VaR to observe diversification effects
	6.	Visualized return distributions using histograms

⸻

📉 Key Insights
	•	NVIDIA shows higher volatility and downside risk compared to JPMorgan
	•	The combined portfolio has lower risk than holding NVIDIA alone
	•	Diversification reduces overall portfolio risk

⸻

📌 Conclusion

Historical simulation offers a straightforward and intuitive way to understand market risk.
This project demonstrates how combining assets can reduce downside risk while maintaining exposure to returns.
