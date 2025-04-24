# Trendy Tastes: Identifying and Visualising Evolving Customer Preferences Using Yelp Reviews
  [Dataset link](https://business.yelp.com/data/resources/open-dataset/)

## Executive Summary
  In the fast-paced restaurant industry, customer preferences are constantly evolving. This project leverages NLP and time-series analysis 
  on Yelp review data to uncover customer       
  sentiments and emerging trends. By focusing on food quality, ambience, and service, we aim to help businesses adapt offerings to meet 
  current market demands. The final output 
  includes a filtered dataset for Arizona and California, sentiment scoring, and a framework for region-based trend visualisation.
  
## Business Impact
  - Restaurant Owners: Gain actionable insights to optimise menus, ambience, and service.
  - Marketers: Design hyper-local campaigns driven by actual customer feedback.
  - Platforms like Yelp: Integrate sentiment-trend APIS for premium business analytics tools.
  
## Problem Statement
  Customer tastes evolve quickly, but businesses struggle to track and respond to these changes in real-time. By analyzing Yelp reviews across selected regions and restaurant types, we 
  aim to answer:
  - What are the dominant sentiments in customer feedback?
  - What trends are emerging across regions or time?
  - How can businesses take proactive actions based on these trends?

## Project Scope
  - Restaurant Focus: Breakfast Places
  - Geographic Scope: Arizona (AZ) and California (CA)
  - Review Categories: Food, Ambience, and Service

## Methodology
  1. Data Extraction
  - Yelp dataset accessed via AWS S3
  - Focused on Arizona & California
  - Filtered to businesses in the restaurant category
  
  2. Sentiment Analysis
  - Processed review texts using NLTK and SpaCy
  - Applied sentiment polarity scoring (positive/negative/neutral)
  
  3. Trend Detection & Topic Modelling
  - Aggregated reviews by date and location
  - Identified rising keywords, cuisines, and ambience preferences over time

## Tools & Technologies
  ## Component	        Tools Used
   - Cloud Storage ->	     AWS S3
   - Data Processing ->	   Python, Pandas, NumPy
   - NLP & Modeling ->	   NLTK, SpaCy, Scikit-learn, TensorFlow (optional)
   - Visualization ->	     Seaborn, Matplotlib, Plotly
   - Database	->           SQL

## Sample Use Cases
 - Detect an increase in mentions of plant-based food in Phoenix → update menu
 - Rising preference for outdoor seating → Adjust ambience plans
 - Negative sentiment about wait times → optimise staffing or service flow

## Key Outputs
 - Cleaned Yelp business and review data for AZ/CA
 - Sentiment distribution plots by category and city
 - Filtered trends showing evolving customer expectations
   
## Future Scope
 - Expand analysis to other U.S. regions
 - Automate trend alerts for restaurant owners
 - Incorporate demographic overlays for even richer insight
 - Real-time trend monitoring dashboard using Streamlit
   
## Data Sources
 - Yelp Open Dataset
 - Kaggle reviews datasets for benchmarking sentiment
 - Public demographic datasets (for future expansion)


