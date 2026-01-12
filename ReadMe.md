# Netflix Content Dashboard (Power BI)

The Power BI dashboard is a tool for visualizing the content library of Netflix.  
The main goal of this project is clear insights, clean layout, and storytelling, not the creation of over-designed visuals.

The data needed for the report is incorporated directly into the Power BI file, so there is no need for external connection, the report just opens and works right away.


# Project Overview
Simple and at the same time practical questions the dashboard is able to answer:

- What was the growth of Netflix content by year?
- Which types of content ruled the platform?
- What countries were the biggest contributors of titles?
- How can one title be examined in detail?

The report consists of two pages, allowing for both high-level analysis and title-level exploration.


# Report Pages
# 1. Overview
The page is designed for quick insights and executive-style review. The catalog of Netflix is being viewed in the summary through this page:
- Content trend over time using the Date Added hierarchy
- Movie vs TV Shows distribution
- Category and genre breakdown
- Geographic distribution of titles by country

<img width="887" height="498" alt="OVERVIEW" src="https://github.com/user-attachments/assets/2ac10458-2196-4b27-8414-51ca32cae1b0" />

# 2. Single Title View
This view exemplifies drill-down analysis and interactive reporting. The user can take a deeper dive into the content through this page:
- Title can be filtered with slicers
- Detailed metadata (type, rating, year added) can be viewed
- Country-level availability and supporting visuals can be seen

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


# Skills Demonstrated

- Power BI report development
- Data modeling with multiple related tables


Programmer Anasieze Uzoma
