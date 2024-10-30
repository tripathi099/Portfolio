
---

# Beats Consumer Insights Data Analytics Externship

**Author:** Shivendra Tripathi  
**Date:** August 2024

---

## Project Overview

This project analyzes customer sentiment for Beats by Dre products and their competitors to extract actionable insights. Through data collection, cleaning, exploratory analysis, sentiment classification, and AI-driven insights, this project aims to highlight areas for product improvements and suggest marketing strategies. By comparing customer sentiment across brands, the analysis helps to position Beats by Dre within a competitive landscape.

---

## Table of Contents

1. [Objective](#objective)
2. [Data Description](#data-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Results](#results)
6. [Future Work](#future-work)
7. [References](#references)

---

## Objective

The primary goal of this project is to:
- Analyze customer feedback on Beats by Dre and competitor products to identify strengths and areas for improvement.
- Utilize AI tools like TextBlob and Gemini AI to classify sentiment and extract unique insights.
- Provide strategic recommendations for product enhancements and marketing based on data-driven insights.

---

## Data Description

- **Source**: Customer reviews were sourced from Amazon using the Oxylabs API, focusing on Beats by Dre products and four competitors: Bose, Sony, JBL, and Sennheiser.
- **Data Volume**: Approximately 1,000 reviews, with each product having a minimum of 100 reviews to ensure sufficient data for meaningful analysis.
- **Attributes**: Key attributes in the dataset include review text, rating, helpful counts, author, and product attributes (e.g., color).

---

## Installation

To set up this project, ensure that Python and the required libraries are installed.


1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

The dependencies include:
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `TextBlob` for sentiment analysis
- `google.generativeai` for AI insights (Gemini AI)

---

## Usage

1. **Data Cleaning**:  
   Run `scripts/data_cleaning.py` to load the raw data, handle missing values, remove outliers, and encode categorical variables.

   ```python
   # Example command to run data cleaning
   python scripts/data_cleaning.py
   ```

2. **Exploratory Data Analysis (EDA)**:  
   Open `notebooks/Beats_Analysis.ipynb` in Jupyter Notebook or Google Colab to explore the data through visualizations, descriptive statistics, and correlation analysis.

3. **Sentiment Analysis**:  
   Use `scripts/sentiment_analysis.py` or the EDA notebook to perform sentiment analysis using TextBlob. This script classifies reviews into positive, neutral, and negative categories.

4. **AI-Generated Insights**:  
   In `notebooks/Beats_Analysis.ipynb`, use Gemini AI to generate additional insights on customer expectations, standout features, and areas for improvement.

---

## Results

### Key Findings

1. **Positive Customer Perception**: Beats by Dre is generally viewed positively, with customers appreciating its design, comfort, and portability.
2. **Quality Control Issues**: ANC functionality and customization options were areas of concern, leading to some negative reviews.
3. **Competitive Positioning**: While Beats holds a strong position, enhancing customization and battery life could improve its market share compared to brands like Bose and Sony.
4. **Unique Selling Points**: AI insights highlighted features like sleep-friendliness and suitability for active lifestyles as unique strengths.

### Visualizations
Key visualizations can be found are:
- **Histogram of Ratings**: Distribution of customer ratings.
- **Sentiment Distribution**: Bar chart showing proportions of positive, neutral, and negative reviews.
- **Correlation Heatmap**: Visual correlation among numeric attributes in the dataset.

### Strategic Recommendations
1. **Product Improvements**: Enhance ANC reliability, introduce customizable sound options, increase battery life, and improve ear tip design for better comfort.
2. **Marketing Strategies**: Emphasize Beats' suitability for active users, highlight any customization features, leverage influencer partnerships, and showcase positive testimonials to build trust.
3. **Future Research**: Track sentiment over time, monitor social media feedback, analyze competitor innovation, and collect demographic data for targeted marketing.

---

## Future Work

To enhance this analysis, consider the following extensions:
- **Longitudinal Analysis**: Conducting a time-based analysis of customer sentiment can reveal shifts in perception and help track the impact of product improvements.
- **Social Media Sentiment Analysis**: Expanding the data sources to include social media can offer real-time insights and highlight emerging trends.
- **Competitor Monitoring**: Regular competitor analysis can help Beats stay informed about industry trends and customer preferences.

---

## References

1. **Data Source**: Amazon customer reviews collected using Oxylabs API.
2. **Tools and Libraries**:
   - **Pandas** and **NumPy**: Data manipulation and processing.
   - **Matplotlib** and **Seaborn**: Data visualization.
   - **TextBlob**: Sentiment analysis.
   - **Gemini AI**: AI-driven insights for advanced analysis.

3. **External Resources**:
   - Oxylabs API documentation for Amazon review extraction.
   - TextBlob and Google Generative AI documentation.

---
