# Laptop Data Analysis - Exploratory Data Analysis (EDA)
### Project Overview
This project focuses on analyzing laptop market data to determine whether pricing is driven primarily by technical specifications or brand identity. By utilizing web scraping and statistical analysis, the project quantifies the "Brand Premium" and identifies key technical drivers of laptop valuation.
+1

### Problem Statement
Consumers and stakeholders often struggle to identify if a laptop's price is justified by its performance or simply influenced by the brand name.


Brand Impact: Does the brand name significantly inflate price regardless of hardware? 


Technical Influence: Which specifications (RAM, ROM, Processor) have the highest correlation with cost? 

### Dataset & Methodology

Data Extraction: Data was scraped using Selenium, which automated a Chrome browser to extract pricing and specification tags from web listings.


Dataset Size: 534 unique laptop listings with 12 attributes.


Key Features: * Categorical: Brand, Processor Type, Model Name, Color.


Technical: RAM (GB), Storage (ROM GB), Screen Size, Weight.


Financial: Current Price, Original Price, Savings, and Discount Percentage.

# Key Findings
### 1. Brand Dominance & "Brand Premium"

High-Tier Brands: Apple and Microsoft lead the market with the highest average prices (₹1.57L and ₹1.44L respectively).


Budget Competitors: Brands like Fujitsu and Acer focus on price-sensitive consumers with the lowest entry points.

### 2. Technical Drivers of Price

RAM is King: RAM capacity has the strongest positive correlation with price (0.45).


Storage Impact: ROM_GB also significantly influences cost (0.40 correlation).


Negligible Factors: Physical attributes like weight and screen size have minimal impact on pricing.

### 3. Discounting Strategies

Aggressive Discounting: Fujitsu (56%) and Lenovo (32%) use high discounts to drive sales volume.


Price Stability: Microsoft maintains the lowest average discount (~2.8%), signaling a "fixed-price" premium strategy.

# Statistical Analysis (Hypothesis Testing)
A One-Way ANOVA test was conducted to determine if brand name significantly affects price.


Null Hypothesis (H0): Average price is the same for all brands.


Result: Rejected the Null Hypothesis (p-value ≈ 0.0).


Conclusion: Brand identity is a statistically significant factor in laptop pricing.

### Value for Money (VFM) Scoring
The analysis categorized laptops based on their specifications vs. price:


9.0 - 10.0 (Excellent): High-end specs at a budget price (likely deep discounts).


7.0 - 8.9 (Great): Solid hardware for a fair market price.


Below 5.0 (Premium): Customers pay extra for the brand name, build quality, or portability.

About the Author
M. Sharath Kumar 


Education: B.sc (MSDS) from Govt Degree College of Khairatabad.


LinkedIn: [https://www.linkedin.com/in/sharath-kumar-morangapalli-99b887261/] 
