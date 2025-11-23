📘 Project Overview

The World Happiness Report provides annual data on global well-being as measured by the Life Ladder score. This project uses that dataset to create a four-graphic narrative arc that illustrates:

Global trends in happiness over time

Differences between the happiest and least happy countries

Long-term shifts in country-level happiness

Relationships between happiness and key socioeconomic factors

All insights are derived from the official dataset:
World Happiness Report (Updated 2024)
Source: /kaggle/input/happiness-report/World-happiness-report-updated_2024.csv

📊 Four-Graphic Narrative Arc

This project includes four original visualizations, each designed to build on the previous one and tell a complete data story:

1. Global Happiness Trend (2005–2023)

Shows the decline in global average Life Ladder scores over time.

2. Top and Bottom 10 Countries (2023)

Highlights the most and least happy countries in the latest available year.

3. Largest Changes in Happiness (2005–2023)

Identifies countries with the greatest improvements and the steepest declines.

4. Correlation Heatmap of Happiness Factors

Examines how GDP, social support, health, freedom, and corruption relate to happiness.

Each visualization is saved as a PNG file in the repository for easy viewing.

🧠 Key Findings

Global happiness declined by 0.83 points from 2005 to 2023.

Finland ranked as the happiest country in 2023 (7.70), while Afghanistan was the least happy (1.45).

Romania, Poland, and Hungary showed the greatest long-term improvements.

Jordan, Lebanon, and Venezuela experienced the largest declines.

The strongest positive correlates of happiness were:
GDP per capita (0.78), Social Support (0.72), Healthy Life Expectancy (0.71).

Perceptions of corruption had a strong negative correlation, indicating that trust in institutions significantly affects happiness.

🧪 Technologies Used

Python 3

Pandas – data cleaning and manipulation

Matplotlib – primary plotting library

Seaborn – enhanced styling for advanced visualizations

NumPy – numerical operations in correlation analysis

Jupyter Notebook – interactive analysis environment


🚀 How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/world-happiness-analysis.git

Open the notebook:

jupyter notebook notebooks/world_happiness_analysis.ipynb


Ensure the dataset is located in the data/ folder.

Run the notebook cells to reproduce all charts and findings.

🙌 Acknowledgements

Data sourced from the World Happiness Report (via Kaggle).
All visualizations and analysis in this repository were developed independently as part of an advanced data storytelling assignment requiring original graphic generation.
