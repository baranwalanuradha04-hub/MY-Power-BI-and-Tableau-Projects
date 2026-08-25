# MY-Power-BI-and-Tableau-Projects
This repository contains Power BI and Tableau projects showcasing my dashboard design and data visualisation skills. Created as part of my learning journey into data and technology.
# Data Visualisation & Reporting Projects 

Two data visualisation projects completed as part of my Data Technician Bootcamp — one in **Power BI** and one in **Tableau** — both focused on transforming raw data and designing interactive reports that turn structured data into clear, actionable business insights, with an emphasis on retail and sales analytics.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<br><br>

## 📊 Power BI Project

Focused on transforming raw data, building DAX calculations, and designing interactive reports.

**Data Transformation & Cleaning (Power Query)**
- Cleaning, shaping, and transforming raw data before loading it into a Power BI data model
- Handling inconsistent, missing, or incorrectly formatted data ahead of analysis
- Loading cleaned data into Power BI to build a reliable foundation for reporting

**DAX Calculations**
- Creating calculated columns to derive new fields from existing data
- Building DAX measures to calculate dynamic values (e.g. totals, averages, growth rates) that respond to report filters and slicers
- Working within a semantic model, configuring relationships between tables to support accurate calculations

**Interactive Report Design**
- Adding slicers and filters so users can interactively explore the data by category, region, or time period
- Structuring reports so that filters apply consistently across multiple visuals on the same page

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<br><br>

## 📈 Tableau Project

Focused on building interactive dashboards and turning data into a clear, explorable visual story.

**Filters & Calculated Fields**
- Adding filters (including Top N and single-value dropdown filters) so users can interactively explore the data by category, region, or time period
- Showing filter cards directly on worksheets and dashboards for easy user interaction
- Creating calculated fields and table calculations (e.g. Percentage of Total) to derive custom metrics not available directly in the source data

**Interactive Dashboard Design**
- Combining multiple worksheets into a single, cohesive dashboard
- Adding titles and formatting for a clean, professional, business-ready presentation
- Applying filters consistently across multiple worksheets on the same dashboard

---

## 📊 Data Visualisation (Both Projects)

Building a variety of visualisations to represent different types of insight:
- 📊 **Bar charts** – comparing values across categories
- 📈 **Line charts** – tracking trends and changes over time
- 🥧 **Pie charts** – showing proportional breakdowns
- 🗺️ **Maps** – visualising geographic or regional data

## 📖 Data Storytelling

- Combining multiple visuals into a single, cohesive report/dashboard that tells a clear story with the data
- Using visuals and interactivity together to highlight key trends, patterns, and outliers relevant to retail and sales performance
- Focusing on turning raw numbers into insights a business audience can act on








## 🎵 Project 3: Spotify Track Insights — Tableau Dashboard


<img width="507" height="392" alt="image" src="https://github.com/user-attachments/assets/42e22956-93db-4044-a539-cfae3a770f99" />

A Tableau dashboard analyzing Spotify track data across music genres, exploring how audio characteristics and popularity relate to one another.

**File:** `Spotify_Track_Insights.twbx`
**Dashboard name:** *Spotify Track Insights Dashboard*

### 📊 Worksheets Included

The dashboard combines 5 worksheets into a single interactive view:

- **Music Genre vs Loudness** — bar chart comparing average loudness across genres (Classical shows the lowest/quietest average)
- **Percentage of Tracks by Popularity** — pie chart showing the split between Low, Medium, and High popularity tracks (71.25% fall into "Medium")
- **Popularity Trend by Genre** — line chart tracking how average popularity has changed from 2000 to 2026, broken out by genre
- **Danceability vs Energy** — scatter plot exploring the relationship between average danceability and average energy per genre
- **Top 10 Popularity by Genre** — bar chart ranking genres by average popularity, led by Folk, Soul, and Jazz

### 🎛️ Interactivity

- **Genre** colour legend for consistent identification across all charts
- **Popularity Group** filter (High / Low / Medium) to highlight or filter across all views
- **Count of Track Id** range filter
- Built in a tiled dashboard layout, with a phone-optimized device preview also configured


### 🎯 Purpose

This project applies core Tableau skills — multi-sheet dashboards, filters, legends, and a variety of chart types (bar, pie, line, scatter) — to a music streaming dataset, telling a data story around genre, loudness, danceability, energy, and popularity trends over time.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<br><br>


## 🌍 Project 4: Global Health Insights — Tableau Dashboard

A Tableau dashboard analyzing global health data across countries and continents, exploring life expectancy trends, disease patterns, and demographic breakdowns to surface key health disparities worldwide.

<img width="547" height="310" alt="image" src="https://github.com/user-attachments/assets/2f6afe3c-015d-4cd1-8256-e5678c6a1384" />


**File:** `Global_Health_Insights_Dashboard.twbx`
**Dashboard name:** *Global Health Insights Dashboard*

<!-- ![Global Health Insights Dashboard](images/global-health-dashboard.png) -->

### 📊 Worksheets Included

The dashboard combines several worksheets into a single interactive view:

- **Life Expectancy by Continent** — bar chart showing average life expectancy for each continent in the most recent year, sorted to highlight the highest and lowest performing regions
- **Life Expectancy Trend** — line chart tracking life expectancy over time for the top 5 countries with the highest average life expectancy, with country used as colour
- **Population by Gender** — pie chart showing population distribution by gender for a selected country in the most recent year, with population values displayed as a percentage of total
- **Life Expectancy vs BMI** — scatter plot exploring the relationship between average life expectancy and average BMI, with individual countries shown as points coloured by continent
- **Top 5 Countries for Cancer Cases** — additional visual highlighting the countries with the highest reported cancer case counts

### 🎛️ Interactivity

- **Country** filter (single-value dropdown) applied to relevant worksheets, letting users select a country and see related details update
- **Continent** filter with a visible filter card on the scatter plot worksheet
- Filters shared across worksheets on the dashboard for coordinated, cross-visual exploration

### 🎯 Purpose

This project applies core Tableau skills — Top N filters, single-value dropdown filters, table calculations (percentage of total), calculated fields, and a variety of chart types (bar, line, pie, scatter) — to a global health dataset, telling a data story around life expectancy, population demographics, and health disparities across countries and continents.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<br><br>
## 💼 Project 5: GB Employment Insights — Tableau Dashboard

A Tableau dashboard analyzing employment trends across Great Britain, exploring how employment figures have changed by city and industry, and identifying the leading industries and sub-industries over time.

<img width="547" height="265" alt="image" src="https://github.com/user-attachments/assets/f655b36e-4d83-4245-8d2c-ba275c82629f" />


**File:** `GB_Employment_Dashboard.twbx`
**Dashboard name:** *Dashboard 1*

<!-- ![GB Employment Dashboard](images/gb-employment-dashboard.png) -->

### 📊 Worksheets Included

The dashboard combines several worksheets into a single interactive view:

- **Avg % Change by City** — chart showing the average percentage change in employment across different cities in Great Britain
- **Avg % Change by Industry** — chart comparing the average percentage change in employment across industries
- **Top 5 Industry** — highlights the five leading industries by employment across the full dataset
- **Top 5 Industry in 2014** — a year-specific breakdown showing the top 5 industries in 2014
- **Top 5 Sub-Industry in 2014** — drills down further into sub-industry level performance for 2014
- **Top Sub-Industry in Cities in 2011** — compares the leading sub-industry across cities for 2011

### 🎛️ Interactivity

- Multiple worksheets combined into a single dashboard for side-by-side comparison
- Year-specific and city-specific views allow users to compare employment performance across different time periods and locations
- Industry and sub-industry level breakdowns support drilling from a high-level view down into more granular detail

### 🎯 Purpose

This project applies core Tableau skills — Top N analysis, percentage change calculations, and multi-level comparisons (industry vs. sub-industry, city vs. national) — to a Great Britain employment dataset, telling a data story around which industries and cities are growing or declining over time.


