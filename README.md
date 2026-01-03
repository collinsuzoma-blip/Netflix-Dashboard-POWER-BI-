# Netflix Content Dashboard (Power BI)

The Power BI dashboard presented in this repository is a tool for visualizing the content library of Netflix.  
The main goal of this project is clear insights, clean layout, and recruiter-friendly storytelling, not the creation of over-designed visuals.

The data needed for the report is incorporated directly into the Power BI file, so there is no need for external connection, the report just opens and works right away.


# Project Overview

Simple and at the same time practical questions the dashboard is able to answer:

- What was the growth of Netflix content by year?
- Which types of content ruled the platform?
- What countries were the biggest contributors of titles?
- How can one title be examined in detail?

The report consists of two pages, allowing for both high-level analysis and title-level exploration.

---

# Report Pages

# 1. Overview
The catalog of Netflix is being viewed in the summary through this page:
- Content trend over time using the *Date Added* hierarchy
- Movie vs TV Shows distribution
- Category and genre breakdown
- Geographic distribution of titles by country

The page is designed for quick insights and executive-style review.

# 2. Single Title View
The user can take a deeper dive into the content through this page:
- Title can be filtered with slicers
- Detailed metadata (type, rating, year added) can be viewed
- Country-level availability and supporting visuals can be seen

This view exemplifies drill-down analysis and interactive reporting.



# Data Structure

The Power BI model is composed of multiple tables that are related to each other and thus representing a realistic catalog-style dataset:

- Titles (main fact table)
- Categories / genres
- Countries released
- Directors
- Cast
- Descriptions

All the relationships are established within Power BI so that filtering and cross-highlighting can take place.



# Skills Demonstrated

- Power BI report development
- Data modeling with multiple related tables
