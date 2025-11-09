# 🎮 Video Game Sales Performance Analysis

## 📊 Overview
This project analyzes **video game sales data** across multiple regions, platforms, genres, and publishers to uncover what factors contribute to **higher global sales**.  
We explore patterns in **sales trends, critic scores, and regional preferences**, along with **predictive modeling and clustering** for deeper insights.

---

## 🎯 Project Goals

### 1. Sales Analysis
- Identify **top-selling games** globally and regionally.
- Compare **sales performance between regions** (NA, EU, JP, Other).
- Determine which **console/platform contributes most** to global sales.
- Evaluate **publishers and developers** dominating sales.
- Analyze **genre popularity** and performance trends.

### 2. Critic Score Impact
- Correlate **critic scores** with **total global sales**.
- Test whether **high-rated games sell more**.
- Compare **Rockstar Games vs. Activision** ratings.
- Identify **developers/publishers with highest average scores**.

### 3. Time-Based Trends
- Study **yearly sales trends** (2000–2024).
- Track **franchise performance** (e.g., GTA, Call of Duty).
- Identify **years with the highest total sales**.
- Detect **platform lifecycle trends**.

### 4. Regional Insights
- Analyze **regional preferences** between Western and Japanese markets.
- Determine **genre and publisher dominance** by region.

### 5. Publisher / Developer Performance
- Compare **average sales per game per publisher**.
- Find the **most profitable publishers** globally.
- Study **developer–publisher partnerships**.
- Analyze **European market performance** by publisher.

### 6. Platform Evolution
- Compare **sales of the same title** across platforms.
- Evaluate **console lifecycle dominance**.
- Analyze **long-term performance of platforms**.

---

## 🧮 Advanced Analytics

| Technique | Purpose |
|------------|----------|
| **Correlation Analysis** | critic_score vs. sales |
| **Regression Model** | Predict total_sales using critic_score, genre, publisher, etc. |
| **Clustering (KMeans)** | Group games by sales and rating patterns |
| **Time Series Analysis** | Detect sales trends over years |

---

## 📈 Final Deliverables

- **EDA Report / Dashboard**
- **Insights Summary** with Visualizations:
  - Top 10 best-selling games
  - Top publishers by total global sales
  - Sales distribution by genre
  - Correlation heatmap (critic_score vs. sales)
  - Yearly sales trend graph

---

## 🧰 Tools & Technologies

| Category | Tools |
|-----------|-------|
| **Language** | Python |
| **Libraries** | pandas, numpy, matplotlib, seaborn |
| **Data Visualization** | Matplotlib |
| **Version Control** | Git & GitHub |

---

## 📂 Dataset
Dataset used: [VGChartz Video Game Sales Dataset](https://www.vgchartz.com/gamedb/)  
or any equivalent open dataset containing:
- `Name`, `Platform`, `Year`, `Genre`, `Publisher`, `Critic_Score`, `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`

  ## 🧾 Dataset Description

| **Field**       | **Description**                                                |
|-----------------|----------------------------------------------------------------|
| `title`         | Game title                                                     |
| `console`       | Console the game was released for                              |
| `genre`         | Genre of the game                                              |
| `publisher`     | Publisher of the game                                          |
| `developer`     | Developer of the game                                          |
| `critic_score`  | Metacritic score (out of 10)                                   |
| `total_sales`   | Global sales of copies (in millions)                           |
| `na_sales`      | North American sales of copies (in millions)                   |
| `jp_sales`      | Japanese sales of copies (in millions)                         |
| `pal_sales`     | European & African sales of copies (in millions)               |
| `other_sales`   | Rest of world sales of copies (in millions)                    |
| `release_date`  | Date the game was released on                                  |
| `last_update`   | Date the data was last updated                                 |


---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/video-game-sales-analysis.git
   cd video-game-sales-analysis
