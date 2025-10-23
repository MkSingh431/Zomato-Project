# Zomato Data Analysis Report

## Executive Summary
This report presents a comprehensive analysis of Zomato restaurant data, focusing on restaurant types, ratings, customer preferences, and ordering modes. The analysis explores data composition, distribution, comparison, and relationships to provide actionable insights for business strategy.

---

## 1. Data Composition

- **Dataset Overview:**  
  The dataset contains information on restaurants, including type, rating, votes, cost for two, and ordering mode.
- **Key Variables:**  
  - *Categorical*: `listed_in(type)`, `online_order`
  - *Numerical*: `rate`, `votes`, `approx_cost(for two people)`
- **Data Quality:**  
  - Ratings were cleaned and converted to numeric values.
  - No major missing values after preprocessing.

---

## 2. Data Distribution

### Restaurant Types
<!-- ![Count of Restaurant Types](figures/restaurant_types_count.png) -->
*Figure: Count of Restaurant Types (see notebook for plot)*  
- **Observation:**  
  The majority of restaurants fall under the "Dine-in" category.

### Votes by Restaurant Type
<!-- ![Votes by Restaurant Type](figures/votes_by_type.png) -->
*Figure: Votes by Restaurant Type (see notebook for plot)*  
- **Observation:**  
  Dine-in restaurants have received the maximum votes, indicating higher customer engagement.

### Rating Distribution
<!-- ![Rating Distribution](figures/rating_distribution.png) -->
*Figure: Rating Distribution (see notebook for plot)*  
- **Observation:**  
  Most restaurants have ratings between 3.5 and 4.5, suggesting generally favorable customer experiences.

### Cost for Two Distribution
<!-- ![Cost for Two Distribution](figures/cost_for_two.png) -->
*Figure: Cost for Two Distribution (see notebook for plot)*  
- **Observation:**  
  The majority of couples prefer restaurants with an approximate cost of 300 rupees.

---

## 3. Data Comparison

### Ratings by Ordering Mode
<!-- ![Ratings by Ordering Mode](figures/rating_by_order_mode.png) -->
*Figure: Ratings by Ordering Mode (see notebook for plot)*  
- **Observation:**  
  Restaurants offering online ordering tend to receive higher ratings compared to those with only offline ordering.

### Restaurant Type vs. Order Mode (Heatmap)
<!-- ![Order Mode Heatmap](figures/order_mode_heatmap.png) -->
*Figure: Restaurant Type vs. Order Mode Heatmap (see notebook for plot)*  
- **Observation:**  
  Dine-in restaurants primarily accept offline orders, while cafes are more likely to receive online orders. This suggests a preference for in-person dining at restaurants and online ordering at cafes.

---

## 4. Data Relationships

- **Votes and Restaurant Type:**  
  There is a strong relationship between restaurant type and the number of votes received, with dine-in establishments leading.
- **Order Mode and Ratings:**  
  Online order availability is associated with higher customer ratings.
- **Cost and Popularity:**  
  Moderate pricing (around 300 rupees for two) is most popular among couples.

---

## 5. Conclusions & Recommendations

- **Dine-in restaurants dominate the market and receive the most customer engagement.**
- **Online ordering is linked to higher ratings; restaurants should consider enabling online orders to boost customer satisfaction.**
- **Cafes benefit more from online orders, while dine-in restaurants thrive on offline, in-person experiences.**
- **Maintaining a moderate price point attracts more couples and increases popularity.**

---

*All plots referenced above are available in the Jupyter notebook. If exporting to PDF, ensure the notebook includes all visualizations inline.*

---

## Appendix

- **Data Cleaning:**  
  Ratings were parsed and converted to numeric values for accurate analysis.
- **Visualization Tools:**  
  All plots were generated using Python libraries: pandas, seaborn, and matplotlib.

---

*Date: [Insert Date]*

---

**Recommendation:**  
Your Jupyter notebook is already well-structured for reporting. For best results, export your notebook as a PDF (with all code cells hidden or removed) to preserve both visualizations and interpretations. Alternatively, use this markdown report and convert it to PDF using a tool like Pandoc or VS Code's Markdown PDF extension.
