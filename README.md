# Customer Shopping Data Analysis using Excel  

## Overview  
This project analyzes customer shopping data to uncover trends in purchasing behavior and sales performance. Using **Excel**, key metrics like **net sales, customer demographics**, and **product category preferences** were visualized through interactive dashboards. The analysis provides actionable insights into purchasing trends, product preferences, and customer engagement, helping optimize marketing strategies and improve sales performance.  

---

## Business Problem  
Retailers need a deeper understanding of purchasing trends to:  
1. **Optimize Inventory Management:** Ensure popular products are always in stock.  
2. **Personalize Marketing Strategies:** Use demographic insights to increase engagement and loyalty.  
3. **Enhance Customer Experience:** Align products and promotions with customer preferences and expectations.  

---

## Dataset  
- **Key Features:**  
  - Customer Demographics: Customer ID, Age, Age Bracket, Gender, Location, Subscription Status.
  - Details: Purchase Amount, Purchase Frequency, Shipping Type, Payment Method.
  - Product Information: Item Purchased, Category, Size, Color, Discount Applied, Promo Code Used.
  - Customer Feedback: Review Rating, Review Rating Bracket.
---

## Methodology  

### 1. Data Cleaning  
- Ensured data accuracy by:  
  - Removing **duplicate transactions** to maintain data integrity.  
  - Standardizing **product categories, sizes**, and **purchase details** for better analysis.  
  - Correcting **missing or inconsistent data**, such as location and purchase amounts.  

### 2. Derived New Columns:
  - Used **Excel IF statements** to create meaningful categories:  
    - **Age Bracket:** Categorized customers into groups such as **"Young Adult"**, **"Middle Age"**, and **"Senior"**:  
      - Formula: `=IF(B2<35, "Young Adult", IF(B2<65, "Middle Age", "Senior"))`  
    - **Review Rating Bracket:** Grouped customer feedback into **Low, Medium, and High Ratings**:  
      - Formula: `=IF(L2<3, "Low Rating", IF(L2<4, "Medium Rating", "High Rating"))`
     
### 3. Data Visualization and Exploratory Analysis  
Excel dashboards and tables were created with dynamic filters to explore key relationships:
1. **Gender vs. Purchase Volume**  
2. **Age vs. Purchase Trends**  
3. **Product Category Preferences**   

---

## Key Insights  
1. **Higher Purchase Volume in Males:**  
   - Males demonstrated higher purchase frequencies across various product categories, suggesting stronger engagement with broader shopping interests.

2. **Middle-Aged Customer Engagement:**  
   - The **30-45 age group** was the most active in purchasing products, highlighting this demographic as a key target segment.

3. **Clothing Preferences Dominating Sales:**  
   - The **Clothing category** was a standout performer, with **size M being the most purchased size for both genders**, indicating high demand and relevance across demographics.

---

## Business Recommendations  
1. **Targeted Inventory Strategies:**  
   - Focus on stocking **medium-sized clothing items** to meet the high demand among customers for popular sizes.

2. **Demographic-Specific Promotions:**  
   - Develop **marketing campaigns targeted at middle-aged customers** to capitalize on their higher purchasing activity.

3. **Category-Based Marketing Initiatives:**  
   - Highlight **popular clothing categories in promotions**, ensuring visibility across key sales channels and product placements.

---

## Tools and Technologies  
- **Microsoft Excel:** Data cleaning, interactive dashboards, filtering, and visualizations.  
- **Tables and Pivot Tables:** Comparative analysis across demographics, product categories, and purchase trends.

---

## Conclusion  
This project leverages Excel’s visualization and filtering tools to uncover critical insights into customer purchasing trends, product preferences, and demographic engagement. Analyzing relationships across gender, age, location, and product categories enables businesses to optimize inventory planning, personalize marketing strategies, and enhance customer satisfaction, ensuring more efficient retail operations and stronger sales performance.

---
