# 🎬 Netflix Content Analysis Dashboard | Power BI

An interactive **Netflix Content Analysis Dashboard** built using Microsoft Power BI to explore Netflix's content library through KPIs, visualizations, filters, and trend analysis.

The dashboard provides an overview of Netflix movies and TV shows, their distribution across countries, genres, release years, and content ratings.

---

## 📌 Project Overview

The objective of this project was to transform Netflix content data into an interactive and visually engaging dashboard that makes it easier to understand the composition and distribution of Netflix's catalog.

The dashboard focuses on answering questions such as:

- How many titles are available?
- How many are Movies and how many are TV Shows?
- Which countries contribute the most content?
- How has the number of titles changed over the years?
- Which content ratings are most common?
- Which genres/categories appear most frequently?

---

# 📊 Dashboard Overview

![Netflix Dashboard](images/netflix-dashboard.png)

The dashboard uses a dark Netflix-inspired theme with red accent colors to create a consistent visual identity.

---

# 🎯 Key Performance Indicators

The dashboard provides four main KPI cards:

| KPI | Description |
|---|---|
| Total Count | Total number of titles in the dataset |
| Total Movies | Number of movie titles |
| Total Countries | Country-related count available in the dataset |
| Total TV Shows | Number of TV show titles |

The values displayed in the dashboard are dynamically affected by the available filters.

---

# 🎛️ Interactive Filters

The dashboard includes several slicers that allow users to explore the dataset interactively.

### Type of Show

Filter the dashboard by:

- Movie
- TV Show

### Released Year

Filter content based on its release year.

### Country

Analyze content associated with different countries.

### Listed In

Filter the dashboard based on genres/categories.

These filters allow users to explore different parts of the Netflix catalog without manually changing individual visuals.

---

# 📈 Dashboard Visualizations

## 1. 🎭 Genre Distribution

A pie chart showing the distribution of titles across major Netflix categories/genres.

This helps identify which types of content are most represented in the dataset.

---

## 2. 📅 Titles by Release Year

A line chart showing the number of Netflix titles by release year.

This helps visualize how Netflix's content catalog has changed over time and highlights periods of significant growth.

---

## 3. 🎬 Movies vs TV Shows

A pie chart comparing the distribution of:

- Movies
- TV Shows

This provides a quick overview of the composition of the Netflix catalog.

---

## 4. 🌍 Top Countries

A bar chart displaying countries with the highest number of associated Netflix titles.

The current dashboard highlights countries such as:

- United States
- India
- United Kingdom
- Japan

The dashboard also contains an `Unknown` category where country information is missing or unavailable.

---

## 5. 🔞 Content Rating Analysis

A bar chart showing the distribution of Netflix titles by content rating.

Examples include:

- TV-MA
- TV-14
- TV-PG
- R
- PG-13
- PG
- TV-Y7
- TV-G
- TV-Y
- NR

This provides an overview of the types of audiences targeted by the content in the dataset.

---

# 🔍 Key Insights

Based on the dashboard:

- Movies represent a larger portion of the catalog than TV Shows.
- The United States has the highest number of associated titles among the countries displayed.
- India is one of the next major contributors to the catalog.
- TV-MA is the most frequently occurring content rating in the dashboard.
- Netflix's catalog shows significant growth in titles released during the later years of the dataset.
- The dataset contains a considerable amount of content associated with multiple genres/categories.

> Note: Insights can change when dashboard filters are applied.

---

# 🛠️ Tools & Technologies

### Power BI

Used to build the interactive dashboard and create data visualizations.

### Power Query

Used for data cleaning and transformation.

Tasks include:

- Data type correction
- Handling missing values
- Cleaning categorical data
- Preparing fields for visualization
- Transforming dataset columns

### DAX

Used to create calculations and KPI measures for the dashboard.

---

# 🧮 Data Analysis

The dashboard uses calculations for metrics such as:

- Total titles
- Total movies
- Total TV shows
- Country-related counts
- Genre/category counts
- Rating counts
- Release-year counts

