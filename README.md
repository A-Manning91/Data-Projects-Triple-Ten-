
# 📊 Restaurant Sales & Performance Dashboard – README

## 🧭 Introduction

This project analyzes sales performance across a network of restaurants using real-world food order data. The objective was to uncover insights about item-level sales, top-performing restaurants, seasonality in revenue, and the relationship between customer ratings and actual sales. The dashboard was created in Tableau and is fully interactive, allowing business stakeholders to explore trends across city, cuisine, and time.

**Project Link:**  
🔗 https://public.tableau.com/views/Manning_FinalProject/Story2

---

## 🔧 What Was Done

- **Data Preparation:**  
  Joined multiple datasets (`orders`, `menu`, `food`, and `restaurant`) directly in Tableau using left joins. Cleaned fields and corrected mismatches between menu prices and actual revenue.

- **KPI Calculation:**  
  Replaced previously calculated revenue fields with actual `sales_amount` from the orders dataset to ensure data accuracy.

- **Dashboard Design:**  
  Created 4 key visualizations:
  1. **Top-Selling Food Items** – Identifies which items bring in the most revenue.
  2. **Highest-Grossing Restaurants** – Shows which restaurants generate the most total sales.
  3. **Monthly Sales Trends** – Reveals peak and low sales periods over time.
  4. **Ratings vs. Revenue** – Examines the relationship between restaurant ratings and revenue performance.

- **Interactive Filters:**  
  Enabled filters for City, Cuisine, and Order Date to allow for granular, localized insights.

---

## 📷 Project Screenshots

**Top-Selling Food Items**  
![Top-Selling Food Items](Screenshot_2025-05-12_at_3.20.27_PM.png)
/Users/alexismanning/Desktop/Screenshot 2025-05-12 at 3.20.27 PM.png

**Highest-Grossing Restaurants**  /Users/alexismanning/Desktop/Screenshot 2025-05-12 at 3.20.32 PM.png
![Highest-Grossing Restaurants](Screenshot_2025-05-12_at_3.20.32_PM.png)

**Monthly Sales Trends**  
![Monthly Sales](Screenshot_2025-05-12_at_3.20.39_PM.png)/Users/alexismanning/Desktop/Screenshot 2025-05-12 at 3.20.39 PM.png

**Ratings vs. Revenue**  
![Ratings vs Revenue](Screenshot_2025-05-12_at_3.21.06_PM.png)/Users/alexismanning/Desktop/Screenshot 2025-05-12 at 3.21.06 PM.png

---

## ✅ Conclusion

- A few food items generate a large share of total revenue.
- Revenue is concentrated among a small number of top-performing restaurants.
- There are clear seasonal peaks and valleys in monthly sales.
- There is a loose but visible correlation between restaurant ratings and total sales.

---

## 💡 Recommendations for the Business

- **Double Down on Top-Selling Menu Items:** Promote and expand the reach of high-revenue dishes.
- **Study the Success of Top Restaurants:** Apply learnings from high performers like Domino’s Pizza to weaker outlets.
- **Plan Around Seasonality:** Launch major promotions during peak months and implement retention tactics during slower months.
- **Balance Ratings and Brand Strategy:** Focus on quality while also building strong branding and pricing models.

---

## 🔭 Ideas for Further Improvement

- Incorporate user demographic analysis by joining the `users.csv` table.
- Add profitability calculations to balance revenue with cost.
- Use geolocation mapping to identify hot zones for specific cuisines or items.
- Automate data refresh using Tableau Public or Tableau Prep flows.

