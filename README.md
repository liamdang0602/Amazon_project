# Amazon Discount Strategy Analysis

## Project Overview
This project analyzes Amazon's discount strategies across various product categories to understand their impact on sales volume, customer satisfaction, and purchasing behavior. The study examines data from 1,462 products, focusing on discount percentages, sales volumes, customer ratings, and feedback to provide insights into optimizing discount policies, particularly for high-ticket items, and improving product quality.

## Objectives
- Evaluate the relationship between discount percentages, sales volume, and customer ratings.
- Identify product categories that benefit most from discounts (e.g., Electronics, Computers & Accessories).
- Highlight categories with poor performance despite discounts (e.g., Home & Kitchen, Office Products).
- Provide recommendations to optimize discount strategies and improve customer satisfaction through enhanced product quality and marketing.

## Dataset
- **Source**: [Amazon Sales Dataset on Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)
- **Size**: 1,462 products
- **Key Metrics**:
  - Price range after discount: ₹39 to ₹77,990
  - Highest discount percentage: 94%
  - Customer participation: 26,765,385 ratings
  - Rating range: 2 to 5

## Key Findings
1. **Discount Effectiveness**:
   - Discounts between 40% and 60% are most effective, driving significant sales volume, especially in Electronics and Computers & Accessories.
   - Discounts below 20% or above 80% have limited impact due to perceived insignificance or skepticism about quality.
   - Home & Kitchen and Office Products show low sales growth despite discounts, indicating other influencing factors.

2. **Customer Satisfaction**:
   - Correlation analysis shows a weak relationship between discounts and customer ratings (-0.16) or rating counts (0.01).
   - Product quality, customer service, delivery time, and brand trust have a greater impact on satisfaction than discounts.
   - Low-rated products, particularly in Home & Kitchen, suffer from quality issues and misleading marketing, leading to negative feedback.

3. **High-Ticket Items**:
   - Electronics dominates high-end products (> $5,000), achieving strong sales with lower discounts (31.8%).
   - Home & Kitchen offers higher discounts (37.98%) but sees lower sales, suggesting issues with product quality or marketing.

4. **Customer Feedback**:
   - Word cloud analysis of low-rated products highlights quality issues ("not working," "problem") and deceptive marketing ("fooled by," "waste of") as primary drivers of dissatisfaction.
   - Home & Kitchen products face criticism for both poor quality and overstated promotional claims.

## Analysis sections:
1. **Distribution of Discount - Discount category**
   ![alt text](download.png)
2. **Discount by main category**
   ![alt text](download-1.png)
3. **Correlation between discounts and ratings**
   ![alt text](download-2.png)
   ![alt text](download-3.png)
4. **Discount and sale volumn**
   ![alt text](download-4.png)
5. **High ticket items**
   ![alt text](download-5.png)
6. **Customer feedback**
   ![alt text](download-6.png)
   ![alt text](download-7.png)

## Recommendations
1. **Optimize Discount Strategies**:
   - Focus on 40%–60% discounts for Electronics and Computers & Accessories to maximize sales.
   - Adjust discount strategies for high-ticket items to balance profitability and customer appeal.

2. **Improve Product Quality**:
   - Enhance quality control for low-rated products, especially in Home & Kitchen, to address functional defects and boost customer satisfaction.
   - Align marketing claims with actual product performance to rebuild trust.

3. **Adjust Strategies for Less Attractive Products**:
   - For Office Products, consider bundled purchase strategies or decoy effects to increase sales of low-to-mid-range items.

## Tools and Libraries
- **Programming Language**: Python
- **Libraries**:
  - **Pandas & NumPy**: Data manipulation and analysis
  - **Matplotlib & Seaborn**: Data visualization (e.g., scatter plots, boxplots, correlation matrices)
  - **Scikit-learn**: Machine learning and statistical modeling
  - **NLTK**: Natural language processing for text analysis (e.g., word clouds)
  - **Statsmodels**: Statistical modeling and correlation analysis

## Repository Structure
- `Amazon project - Tung Dang.pdf`: The main project report containing detailed analysis, figures, and recommendations.
- `data/`: (Placeholder) Directory for raw and processed datasets (not included in this repository).
- `figures/`: (Placeholder) Directory for visualizations such as correlation matrices, scatter plots, and word clouds referenced in the report.

