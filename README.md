# 🏆 Sales & Ranking Dashboard
---

## 📎 Dashboard Preview

📄 **[Click here to view the full dashboard — Budget & Ranking.pdf](https://github.com/mohamed1710-1998/Budget-Ranking-Dashboard/blob/main/Budget%20%26%20Ranking.pdf)**

---

## 🧩 Project Overview

A multi-page Power BI dashboard built to analyze **FMCG sales performance** across supervisors, salespersons, product groups, and sales channels — covering the period **2019 to 2021**.

The dashboard combines a **Sales Overview page** for macro-level analysis and a **Ranking Dashboard page** that highlights individual salesperson performance and goal achievement — making it a powerful tool for sales management and incentive tracking.

---

## 🎯 Business Questions Answered

- What is the total revenue and order volume across all channels?
- How does quarterly revenue trend across 2019–2021?
- Which supervisors and salespersons generate the most revenue?
- Which product groups drive the highest sales?
- How is revenue distributed across Retail, Distributor, and Online channels?
- Who is the top-performing salesperson and what is their achievement rate?

---

## 📌 Key KPIs

### Sales Dashboard
| Metric | Value |
|---|---|
| 💰 Total Revenue | **$17,909,232** |
| 📦 Total Orders | **52,560** |
| 💵 ATP (Avg Ticket Price) | **$341** |

### Ranking Dashboard
| Metric | Value |
|---|---|
| 💰 Top 3 Revenue | **$10,456,021** |
| 📦 Top 3 Orders | **26,382** |
| 💵 Top 3 ATP | **$396** |
| 🏆 Best Salesperson | **Carla Ferreira — $4,707,403 \| 9,570 orders** |

---

## 📄 Dashboard Pages

### 1️⃣ Sales Dashboard

**KPI Cards:** Revenue $17.9M \| Orders 52,560 \| ATP $341

**Revenue and Orders by Year and Quarter** — Combo chart (bar + line):
- Covers Q1 2019 → Q1 2021
- Revenue peaks in **Q3–Q4 2020**
- Orders trend upward through 2020 then dip in 2021

**Supervisor Performance Table:**
| Supervisor | Revenue | Orders | ATP |
|---|---|---|---|
| Diego Araujo | $6,315,114 | 15,471 | $408 |
| Diogo Carvalho | $6,098,516 | 18,267 | $334 |
| Sofia Ribeiro | $3,113,650 | 12,025 | $259 |
| Emily Rocha | $1,560,528 | 4,368 | $357 |
| Fernando Silva | $821,425 | 2,429 | $338 |
| **Total** | **$17,909,232** | **52,560** | **$341** |

**Revenue by Product Group** — Top performers:
| Product | Revenue |
|---|---|
| Wheat Flour | $4,473K |
| Oil | $2,890K |
| Yeasts | $2,201K |
| Flour | $1,662K |
| Liquor | $1,139K |

**Revenue by Channel** — Donut chart:
- 🛒 Retail: **$9M (48.56%)**
- 🏭 Distributor: **$6M (34.05%)**
- 🌐 Online: **$3M (17.39%)**

**Orders by Product Category** — Donut chart:
- 🍞 Food: **90.21%**
- 🥤 Drink: **9.79%**

---

### 2️⃣ Ranking Dashboard

**Dynamic salesperson leaderboard with photo, rank, revenue & achievement %:**

| Rank | Salesperson | Revenue | Achievement |
|---|---|---|---|
| 🥇 1 | Carla Ferreira | $4,707,403 | 110% |
| 🥈 2 | Julio Lima | 3,301,482 | 122% |
| 🥉 3 | Gustavo Gomes | 2,447,136 | 108% |
| 4 | Felipe Goncalves | $1,676,337 | 74% |
| 5 | Leonardo Cardoso | $1,607,712 | 94% |
| 6 | Isabella Sousa | $870,302 | 79% |
| 7 | Kaua Araujo | $821,425 | 106% |
| 8 | Mateus Costa | $785,241 | 88% |
| 9 | Gustavo Barros | $664,172 | **181%** |
| 10 | Julia Silva | $652,073 | 119% |
| 11 | Estevan Souza | $349,897 | 96% |
| 12 | Julieta Gomes | $26,054 | 125% |

> 🏆 **Carla Ferreira** is the #1 salesperson with $4.7M revenue and 9,570 orders

---

## 🔍 Key Insights

- 🏆 **Carla Ferreira** leads all salespersons with $4.7M — nearly 3x the next ranked seller
- 🎯 **Gustavo Barros** achieved **181% of target** — highest achievement rate despite lower revenue
- 🛒 **Retail channel dominates** at 48.56% of total revenue
- 🍞 **Food products** represent 90.21% of all orders — core business driver
- 🌾 **Wheat Flour** is the top product group at $4.47M
- 📈 **Diego Araujo** leads supervisors with $6.3M revenue and highest ATP ($408)
- 📅 Revenue peaked in **Q3–Q4 2020** before declining in early 2021

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Microsoft Excel** | Data source & preparation |
| **Power BI Desktop** | Data modeling, DAX measures, visualization |
| **DAX** | Revenue, ATP, ranking, achievement % calculations |
| **Power Query** | Data transformation & loading |

---

## 📂 Repository Structure

```
sales-ranking-dashboard/
│
├── Budget & Ranking.pbix          # Power BI report file
├── Budget & Ranking.pdf           # Full dashboard preview (PDF)
├── Budget & Ranking.zip           # Source dataset
└── README.md                      # Project documentation
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open with **Power BI Desktop** (free — download from Microsoft)
3. Navigate between **Sales Dashboard** and **Ranking Dashboard** using the left sidebar
4. Use the filter panel to slice by supervisor, channel, or time period
5. To preview without Power BI — open `Budget___Ranking.pdf`

---

## 👤 Author

**Mohamed Samir**
- 💼 [LinkedIn](https://www.linkedin.com/in/mohamed-samir-gaber/)
- 📧 mohamed171019988@gmail.com

---

*Dataset: FMCG sales dataset covering 2019–2021 — built for sales performance analysis*
