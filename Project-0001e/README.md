![Project-0001e](https://github.com/isachenko-andrii/Excel-Sheets-projects/raw/main/Project-0001e/Project-logo.png)
## Project title: Brazilian E-Commerce Sales & Inventory Optimization (ABC/XYZ Analysis)  
  
## Project description  
  
This project focuses on a comprehensive analysis of the Brazilian Olist e-commerce dataset. The goal is to optimize inventory management and sales strategy by performing ABC/XYZ analysis. This allows the business to identify high-profit "star" products, detect "dead stock" in category C, and understand the stability of demand for effective procurement planning.  
  
## Data used  
  
The analysis uses open-source data from the Olist Store, the largest department store in Brazilian marketplaces.  
    • Source: [Kaggle (Brazilian E-Commerce Public Dataset by Olist)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
    • Sample size: 100,000+ orders from 2016 to 2018.  
    • Data composition: Relational structure including tables for orders, product items, product category translation, and timestamps.  
    
## Technology stack  
  
    • Tools: Microsoft Excel / Google Sheets  
    • Key Functions: XLOOKUP (data merging), Pivot Tables (aggregation), SUMIFS, STDEV.P & AVERAGE (for CV calculation), IFS (for classification).  
    • Visualization: Pareto Chart, Scatter Plot (ABC/XYZ Matrix), Interactive Slicers.  
    
## Key stages of analysis  

    1. Data Merging & Cleaning: Unifying multiple CSV files into a master sheet using XLOOKUP. Translating Portuguese categories to English and cleaning date formats.  
    2. Feature Engineering: Calculating Revenue, Margin, and Order Frequency per category/product.  
    3. ABC Analysis: Ranking products by their contribution to total revenue (A: 80%, B: 15%, C: 5%).  
    4. XYZ Analysis: Calculating the Coefficient of Variation ($CV$) for each category to determine demand stability across months.  
    5. Cross-Matrix Construction: Combining ABC and XYZ results into a final 9-cell matrix (e.g., AX, BZ, CY) to generate business recommendations.  
    
## Key insights  
  
    • Revenue Drivers (Group A): Identified that top 10% of categories (like health_beauty and watches_gifts) generate over 70% of total revenue.  
    • Demand Stability: Categories in the AX group show high revenue and low volatility, making them ideal for automated restocking.  
    • Optimization Potential: Group CZ contains items with sporadic sales and low margins; reducing this stock could free up ~15% of tied-up capital.  
    • Seasonality: Specific spikes detected in Q4 (Black Friday effect), impacting the XYZ stability ratings for electronics.  
    
## Visualizations  

The project includes:  
    • Pareto Chart: Visualizing the 80/20 rule for product revenue.  
    
    • ABC/XYZ Matrix (Heatmap): A 3x3 grid showing the distribution of categories.  
      
    • Sales Dynamics: Monthly revenue trends with category filters.  
    
    • Category Breakdown: Treemap of revenue distribution by English category names.  
    
## Project structure  
  
**Project-0001e**/ — project directory  
| - data/ — project data  
|| - raw/ — original Olist CSV files (orders, items, products)  
|| - processed/ — final Excel/Sheets file with formulas and master table  
| - docs/ — documentation and ABC/XYZ methodology explanation  
| - results/ — screenshots of the Dashboard and final insights  
| - Project-Logo.png — project cover  
| - README.md — project description  
    
## How to Use  

To explore this analysis:  
    1. Download the project file  
       Project-0001e.xlsx (or link to Google Sheets) 
       File location: [Link to your file]  
    2. Access the Dataset  
       If you wish to see the raw data, download it from Kaggle:  
       Kaggle: Brazilian E-Commerce Public Dataset  
    3. Interacting with the Dashboard  
        ◦ Open the Dashboard tab.  
        ◦ Use Slicers to filter data by time period or product category.  
        ◦ Observe how the ABC/XYZ Matrix updates based on the selected filters.  
        
## Contact  
    
**Name:** Andrii Isachenko  
**LinkedIn:** [Andrii Isachenko](https://www.linkedin.com/in/isachenko-andrii/)  
**E-mail:** isao.datastudio@gmail.com  
  
## Acknowledgments  
  
Thanks to [Olist](https://www.olist.com/) for providing this rich dataset for the data community.  
Special thanks to the [Kaggle](https://www.kaggle.com/) platform for hosting the data.  
Project Status: Completed. Planned future update: Adding RFM (Recency, Frequency, Monetary) analysis for customer segmentation.  
  
**License:** MIT License.
