# Netflix Content Intelligence Dashboard (POWER BI)
I built an interactive Power BI project analyzing regional, age-group, and genre patterns across movies vs TV shows. Built interactive dashboards to uncover audience preferences, content distribution, and viewing trends for data-driven content strategy.

# Core Tables
Dimensional (Lookup) Tables:

- Listed_in → genres
- Description → text description
- Directors → director names
- Cast → actors and actresses
- Countries → list of countries available

- Relationships:
titles.show_id (1) ➝ many (listed_in.show_id, netflix_cast.show_id, netflix_directors.show_id, netflix_countries.show_id, description.show_id)


# Data Transformation (Power Query)
These transformations ensure accurate visuals and filters. You likely performed the following steps:

- Cleansed text columns (remove nulls, trim whitespace)
- Split multi-values (e.g., multiple cast members)
- Created date hierarchies (Year, Month)
- Consolidated genres (cleaned duplicates)

# Project Overview
Simple and at the same time practical questions the dashboard is able to answer:

- What was the growth of Netflix content by year?
- Which types of content ruled the platform?
- What countries were the biggest contributors of titles?
- How can one title be examined in detail?

The report consists of two pages, allowing for both high-level analysis and title-level exploration.

# Architectural Flow (Annotated)
<img width="360" height="479" alt="SYSTEM FLOW" src="https://github.com/user-attachments/assets/b3838bd5-2f37-4952-8bf6-05dc4c0719f6" />


# Report Pages
# 1. Overview
The page is designed for quick insights and executive-style review. The catalog of Netflix is being viewed in the summary through this page:
- Content trend over time using the Date Added hierarchy
- Movie vs TV Shows distribution
- Category and genre breakdown
- Geographic distribution of titles by country
- World map of availability

<img width="887" height="498" alt="OVERVIEW" src="https://github.com/user-attachments/assets/2ac10458-2196-4b27-8414-51ca32cae1b0" />

# 2. Single Title View
This view exemplifies drill-down analysis and interactive reporting. The user can take a deeper dive into the content through this page:
- Title can be filtered with slicers
- Detailed metadata (type, rating, year added, Description, Cast list, Director, Countries map, Genre tag (Listed_in)) can be viewed
- Country-level availability and supporting visuals can be seen
- Dropdown slicer for selecting a single show

<img width="883" height="495" alt="SINGLE TITLE VIEW" src="https://github.com/user-attachments/assets/809fc200-bd4a-4954-89fe-51964a8382a0" />

# Data Structure
All the relationships are established within Power BI so that filtering and cross-highlighting can take place. The Power BI model is composed of multiple tables that are related to each other and thus representing a realistic catalog-style dataset:

- Titles (main fact table)
- Categories / genres
- Countries released
- Directors
- Cast
- Descriptions

<img width="743" height="494" alt="MODEL" src="https://github.com/user-attachments/assets/186a6b45-1455-4696-a5a9-346008b7eed8" />




Programmer Anasieze Uzoma
