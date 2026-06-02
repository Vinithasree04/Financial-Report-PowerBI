# 📊 Financial Dashboard — Power BI

An interactive **4-page Financial Dashboard** built with Microsoft Power BI, analyzing Sales, Profit, and Units Sold across products, segments, countries, and time — using the Microsoft Financials sample dataset.

---

## 🖼️ Dashboard Preview

### 🏠 Index Page

![Index Page](screenshots/index.png)

### 📈 Sales Report

![Sales Report](screenshots/Sales.png)

### 💰 Profit Report

![Profit Report](screenshots/Profit.png)

### 📦 Units Sold Report

![Units Sold Report](screenshots/UnitsSold.png)

>

---

## 📁 Project Structure

```
Financial_Dashboard/
│
├── Financial_Dashboard.pbix       # Main Power BI report file
├── README.md                      # Project documentation
└── screenshots/                   # Dashboard preview images
    ├── index.png
    ├── sales_report.png
    ├── profit_report.png
    └── units_sold_report.png
```

---

## 📄 Report Pages

| #   | Page                  | Description                                                |
| --- | --------------------- | ---------------------------------------------------------- |
| 1   | **Index**             | Home page with navigation buttons to all 3 report sections |
| 2   | **Sales Report**      | Revenue analysis — $118.73M total sales                    |
| 3   | **Profit Report**     | Profit breakdown — $16.89M total profit                    |
| 4   | **Units Sold Report** | Volume analysis — 1.13M total units sold                   |

---

## 📊 Dashboard Features

Each report page (Sales / Profit / Units Sold) contains a consistent layout:

### 🔢 KPI Summary Cards

| Metric                | Value    |
| --------------------- | -------- |
| **Sum of Sales**      | $118.73M |
| **Sum of Profit**     | $16.89M  |
| **Sum of Units Sold** | 1.13M    |

### 📉 Charts & Visuals

| Visual           | Fields Used                   | Insight                              |
| ---------------- | ----------------------------- | ------------------------------------ |
| **Column Chart** | Product vs Sales/Profit/Units | Paseo leads with $33M in Sales       |
| **Bar Chart**    | Segment vs Sales/Profit/Units | Government is the top segment ($53M) |
| **Donut Chart**  | Discount Band                 | High / Low / Medium / None breakdown |
| **Area Chart**   | Month vs Sales/Profit/Units   | October peaks at $21.7M in Sales     |

### 🔽 Slicers / Filters

- **Year** — Filter by 2013 or 2014
- **Country** — Canada, France, Germany, Mexico, United States

---

## 📌 Key Insights (Sales Report)

- 🏆 **Top Product by Sales:** Paseo — $33M
- 🏢 **Top Segment:** Government — $53M
- 📅 **Peak Month:** October — $21.7M
- 🌍 **Countries Covered:** Canada, France, Germany, Mexico, United States
- 🏷️ **Discount Bands:** High (6.69%), Medium (29.17%), Low (31.48%), None (32.66%)

---

## 🗃️ Data Source

Built on the **Microsoft Financials** sample dataset with the following key fields:

| Field           | Description                                                                            |
| --------------- | -------------------------------------------------------------------------------------- |
| `Sales`         | Total revenue generated                                                                |
| `Profit`        | Net profit earned                                                                      |
| `Units Sold`    | Number of units sold                                                                   |
| `Product`       | Product name (Paseo, VTT, Velo, Amarilla, Montana, Carretera)                          |
| `Segment`       | Business segment (Government, Small Business, Enterprise, Midmarket, Channel Partners) |
| `Country`       | Country of sale                                                                        |
| `Discount Band` | Discount tier (High, Low, Medium, None)                                                |
| `Date Month`    | Month of the transaction                                                               |
| `Year`          | Year (2013 / 2014)                                                                     |

---

## 🚀 Getting Started

### Prerequisites

- [Microsoft Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494) — Free download

### Steps to Open

1. **Clone this repository**

   ```bash
   git clone https://github.com/your-username/Financial-Dashboard.git
   cd Financial-Dashboard
   ```

2. **Open Power BI Desktop**

3. **Load the report**
   - Go to **File → Open report → Browse**
   - Select `Financial_Dashboard.pbix`

4. **Explore the dashboard**
   - Start at the **Index** page
   - Click any button (Sales Report / Profit Report / Units Sold Report) to navigate
   - Use the **Year** and **Country** slicers to filter data

---

## 🎨 Design

| Property          | Detail                                       |
| ----------------- | -------------------------------------------- |
| **Theme**         | Fluent2 (Microsoft Modern Design)            |
| **Color Palette** | Pink / Magenta gradient                      |
| **Canvas Size**   | 1920 × 1080 (Full HD)                        |
| **Navigation**    | Index page with button-based page navigation |

---

## ✅ Features

- 🏠 Centralized **Index page** with clickable navigation
- 🔗 **Cross-filtering** — click any visual to filter others on the page
- 📅 **Year slicer** for 2013 / 2014 comparison
- 🌍 **Country slicer** for regional filtering
- 📊 Consistent **KPI cards** across all report pages
- 🎨 Custom **pink/magenta theme** with logo branding
- 📐 **Full HD (1920×1080)** canvas layout

---





## 👩‍💻 About Me


A Vinitha Sree 
Aspiring Data Analyst passionate about turning data into meaningful insights using Excel, Power BI, and SQL.

- 🐙 GitHub: [Vinitha_Github](https://github.com/Vinithasree04)
- 💼 LinkedIn: [Vinitha-linkedin](www.linkedin.com/in/vinithasree)
- 📧 Email: vinithasree04@gmail.com
---

