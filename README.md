# Benfords-law-stars-dataset
A data science project analyzing the adherence of star dataset measurements (distance, magnitude, parallax) to Benford's Law using Python. Includes statistical tests, visualizations, and an H-R diagram approximation.

📌 Project Title:
Benford’s Law in Stars_dataset

👨‍💻 Team Name:
Neural Theorems

👥 Team Members:
Akash Dhar Dubey – akash.dubey01@adypu.edu.in

Yash Kishor Mali – yash.mali@adypu.edu.in

Himanshu Gulhane – himanshu.gulhane@adypu.edu.in

Ayush Kumar – ayush.kumar01@adypu.edu.in

📋 Table of Contents:
Project Overview

What is Benford’s Law?

Dataset Description

Data Cleaning and Preparation

Benford’s Law Analysis

Chi-Square Test

H-R Diagram Approximation

Observations

Individual Contributions

Conclusion

📌 What is Benford’s Law?
Benford’s Law (First-Digit Law) predicts the frequency distribution of leading digits in many real-life sources of data.
Formula:

p(d) = log₁₀(1 + 1/d)

Where d is the leading digit (1 to 9).
For example:

Digit 1 appears ~30.1% of the time

Digit 2 appears ~17.6%, and so on...

📊 Implementation Highlights:
Dataset from Google Sheets – Contains stellar attributes like Distance (ly), Visual & Absolute Magnitude, and Parallax.

Converted columns to numeric, cleaned missing data.

Extracted leading digits from each value.

Compared Observed Frequencies vs Expected (Benford).

Visualized results using matplotlib and seaborn.

🔬 Statistical Analysis:
Applied Chi-Square Test to validate the distribution.

P-value > 0.05 in most cases → Suggests the dataset aligns with Benford’s Law.

🌟 H-R Diagram Approximation:
Plotted Visual Magnitude vs Absolute Magnitude

Used scatter plot to emulate Hertzsprung–Russell Diagram.

Verified star brightness and classification consistency.

📌 Observations:
Data follows Benford's Law well.

No signs of fabrication or anomalies.

Indicates dataset is natural and reliable for astronomical studies.

👨‍🔬 Individual Contributions:
Akash Dhar Dubey: Data Cleaning, Numeric Conversion, Benford's Function

Yash Kishor Mali: Chi-Square Implementation, Statistical Interpretation

Himanshu Gulhane: H-R Diagram Creation, Spectral Visualization

Ayush Kumar: Frequency Extraction, Final Result Compilation

🙏 Conclusion:
Our analysis verifies that the stellar data follows Benford’s Law, indicating high data authenticity and reliability for further astrophysical research.

Would you also like this as a downloadable .txt or .md file?








