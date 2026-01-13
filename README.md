# 📊 Google Trends Analysis Dashboard

## 🧠 Overview

This project is an **interactive Power BI dashboard** designed to
visualize and analyze **Google Trends data** for popular search topics
over time.
It provides insights into the relative search interest of various
keywords across countries, highlighting **rising** and **top-performing
topics** globally and regionally.

The dashboard enables users to: - Track keyword performance over time.
- Compare interest across regions and countries.
- Identify top and emerging search trends.
- Explore topic types (e.g., Tournament, Sports Equipment, Team).

------------------------------------------------------------------------

## 📁 Project Files

  `googletrends.pbix`                           Main Power BI project file
                                                containing visuals, DAX measures,
                                                and data connections.

  `Countries_with_Flags_URL_with_Regions.csv`   Lookup table containing country
                                                names, flag image URLs, and
                                                associated regions.

  `googletrends.pdf`                            Exported report showing the final
                                                dashboard visuals.

------------------------------------------------------------------------

## 🧩 Data Sources

1.  **Google Trends Data**
    -   Extracted using the [Google
        Trends](https://trends.google.com/trends/) web interface or
        API.
    -   Includes keywords such as *Cricket, India, WWE, Movie,* and
        *Software Developer*.
    -   Metrics represent *relative interest* (0--100) over time.
2.  **Countries with Flags (Supplementary)**
    -   CSV file providing country metadata:
        -   `Country`
        -   `Country code`
        -   `Flag` (from [Flagcdn.com](https://flagcdn.com))
        -   `Region` (Africa, Asia, Europe, etc.)

------------------------------------------------------------------------

## 🧮 Key Metrics

  -----------------------------------------------------------------------
  Metric                      Description
  --------------------------- -------------------------------------------
  **Total Interest**          Sum of interest values for a keyword across
                              the selected date range.

  **Top Keywords**            Keywords with consistently high search
                              interest.

  **Rising Keywords**         Keywords showing the most growth in recent
                              trends.

  **Category Type**           Classification such as Tournament, Sport,
                              Team, or Equipment.
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 🖥️ Dashboard Sections

1.  **Keyword Trend Over Time** --- Line charts showing interest for
    each keyword from 2018--2025.
2.  **Geographical Analysis** --- Country-wise breakdown of keyword
    popularity, enhanced with flag icons.
3.  **Top vs Rising Keywords** --- Comparative visualization of
    high-performing vs newly trending topics.
4.  **Filter Controls** --- Date range slicers and keyword filters for
    custom exploration.

------------------------------------------------------------------------

## ⚙️ Setup Instructions

1.  Open `googletrends.pbix` in **Power BI Desktop**.

2.  Go to **Transform Data → Data Source Settings**.

3.  Update the file path for:

        Countries_with_Flags_URL_with_Regions.csv

    to your local system path (e.g.,
    `C:\Projects\GoogleTrends\Countries_with_Flags_URL_with_Regions.csv`).

4.  Click **Apply Changes** and **Refresh** the data model.

5.  (Optional) Export as PDF or publish to **Power BI Service** for
    online access.

------------------------------------------------------------------------

## 🧱 Tools & Technologies

-   **Power BI Desktop**
-   **Google Trends API / Web Data**
-   **Power Query (M Language)**
-   **DAX (Data Analysis Expressions)**
-   **FlagCDN Image URLs**

------------------------------------------------------------------------



