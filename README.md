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

🔑 Key Insights
	•	NVIDIA exhibits higher volatility and downside risk compared to JPMorgan, reflected in its higher 5% Value at Risk (VaR) of 3.5%, while JPMorgan’s VaR is 1.7%, indicating more stable daily price movements.
	•	Portfolio diversification reduces downside risk, as combining JPMorgan and NVIDIA into a single portfolio lowers the estimated VaR to 2.4%, compared to holding NVIDIA alone.
	•	Risk reduction is achieved without eliminating growth exposure, demonstrating how diversification cushions portfolio losses by balancing high-volatility assets with more stable ones.
	
⸻

⚠️ Limitations
	•  Single-day risk horizon:
       The Value at Risk (VaR) estimates in this project are based on a one-day holding period. For investors with longer holding periods, risk can accumulate over time, meaning actual losses over weeks or months may be higher than daily        VaR suggests.
	•  Historical dependence:
       The analysis relies on historical price movements and assumes past return patterns are indicative of future risk. Sudden structural market changes may not be captured.
	•  Correlation stability assumption:
       Diversification benefits assume stable correlations between assets. During periods of market stress, correlations can increase, reducing the effectiveness of diversification and leading to higher-than-expected losses.
	•  VaR tail limitation:
       VaR identifies a loss threshold but does not describe the severity of losses beyond that threshold, potentially understating extreme downside risk.

⸻

🚀 Future Improvements
	•   Multi-day Value at Risk:
        Extend the analysis by scaling VaR to longer holding periods (e.g., weekly or monthly) to reflect the investor's time horizon.
	•   Rolling risk estimates:
        Implement rolling VaR calculations to capture changes in volatility and risk dynamics over time.
	•	Expected Shortfall (ES):
        Complement VaR with Expected Shortfall to measure average losses beyond the VaR threshold, providing a more complete view of tail risk.
	•	Correlation and stress testing:
        Analyze how changing correlations during market stress affect portfolio risk and perform stress tests under extreme market scenarios.
	•	Expanded portfolio analysis:
       Include additional assets across different sectors to further evaluate diversification benefits.

⸻

📌 Conclusion

This project demonstrates how Value at Risk and diversification can be used to quantify and manage downside risk in equity portfolios. While the analysis highlights meaningful risk reduction through asset combination, it also acknowledges the limitations of single-period VaR estimates and the importance of considering correlation dynamics and tail risk in real-world applications.
