# 120 Years of Olympics Dashboard

## Snapshot of Dashboard (Power BI Service)

![Dashboard_Snapshot](https://app.powerbi.com/view?r=eyJrIjoiZDBhZjgzNGQtYjk3MS00NWNiLWEyZWUtYjRhMmY3NTMxYmY1IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

### Dashboard Link: [Power BI Dashboard Link](https://github.com/kscheran93/Power-BI-Olympics-120-years-of-history-dashboard/blob/main/olympic%20picture.png)

### Dataset link : [link](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
## Problem Statement

This dashboard offers a comprehensive analysis of 120 years of Olympic history, including athlete performances, medal distributions, and trends over time. By analyzing various aspects such as sports, gender, year, city, medal types, and seasons, stakeholders can gain valuable insights into Olympic trends, key contributors, and evolving participation patterns.

### Steps Followed

- **Step 1:** Loaded the dataset into Power BI Desktop from an Excel file containing data on Olympic athletes and their results from the last 120 years.

- **Step 2:** Cleaned and prepared the data using Power Query Editor, addressing issues like missing values, erroneous entries, and ensuring data consistency.

- **Step 3:** Applied a cohesive visual theme with a custom background color of `#1F2A38` to maintain a modern and visually appealing design.

- **Step 4:** Created the following visualizations:
  
  1. **Clustered Bar Chart (Horizontal):** 
     - **Chart Title:** "Countries' Total Medals"
     - **Y-Axis:** `Team` (Countries)
     - **X-Axis:** Count of `Medals`
     - **Insights:** This chart showcases the total number of medals won by each country, highlighting the top-performing nations in Olympic history.
  
  2. **Clustered Bar Chart (Horizontal):**
     - **Chart Title:** "Athletes by Total Medals"
     - **X-Axis:** `Name` (Athlete Names)
     - **Y-Axis:** Count of `Medals`
     - **Insights:** Identifies the athletes with the highest medal counts, providing insights into individual achievements.

  3. **Clustered Column Chart:** 
     - **Chart Title:** "Total Athletes by Year"
     - **X-Axis:** `Year`
     - **Y-Axis:** Count of `ID` (Unique Athlete IDs)
     - **Insights:** Shows trends in athlete participation over the years, highlighting peaks and dips in Olympic attendance.

  4. **Scatter Chart:**
     - **Chart Title:** "Height and Weight Correlation"
     - **X-Axis:** `Height`
     - **Y-Axis:** `Weight`
     - **Insights:** Analyzes the correlation between athletes' heights and weights, which can vary by sport or gender.

  5. **Clustered Column Chart:** 
     - **Chart Title:** "Top 10 Sports by Total Medals"
     - **X-Axis:** `Sports`
     - **Y-Axis:** Count of `Medals`
     - **Filters:** Applied to show the top 10 sports by the total number of medals won.
     - **Insights:** Highlights the sports with the most medal awards, indicating which sports have seen the most success over the years.

  6. **Clustered Column Chart:** 
     - **Chart Title:** "Athletes by Age"
     - **X-Axis:** `Age`
     - **Y-Axis:** Count of `ID` (Unique Athlete IDs)
     - **Insights:** Displays the age distribution of athletes, providing insights into the average age of Olympic participants.

  7. **Clustered Column Chart:** 
     - **Chart Title:** "Athletes by Weight"
     - **X-Axis:** `Weight`
     - **Y-Axis:** Count of `ID`
     - **Insights:** Examines the distribution of athletes by weight, which may be influenced by the sport they participate in.

  8. **Clustered Column Chart:** 
     - **Chart Title:** "Athletes by Height"
     - **X-Axis:** `Height`
     - **Y-Axis:** Count of `ID`
     - **Insights:** Shows how athletes are distributed by height, which could provide insights into the physical attributes of top-performing athletes.

- **Step 5:** Added six filters for a more interactive experience:
  - **Sport:** Filter by the type of sport to narrow down visualizations to specific sports.
  - **Sex:** Filter by gender (Male/Female) to analyze trends based on athlete gender.
  - **Year (Start Date to End Date):** Filter by the year range to focus on specific Olympic Games.
  - **City:** Filter by host city to analyze the performance and participation in specific locations.
  - **Medal:** Filter by medal type (Gold, Silver, Bronze) to analyze the distribution of specific medals.
  - **Season:** Filter by Summer or Winter Games to separate analyses by Olympic season.

- **Step 6:** Published the report to Power BI Service for broader accessibility.

## Insights

The dashboard provides several key insights into Olympic history:

### [1] Countries' Total Medals
   - The horizontal bar chart highlights the top-performing nations, showcasing their total medal counts and revealing dominance in specific regions.

### [2] Athletes by Total Medals
   - This chart identifies the most decorated athletes in Olympic history, showcasing the individuals with the highest medal counts.

### [3] Total Athletes by Year
   - The clustered column chart shows trends in athlete participation over time, highlighting periods of growth or decline in the number of participants.

### [4] Height and Weight Correlation
   - The scatter chart provides a visual representation of the relationship between athlete height and weight, which can inform on the physical characteristics prevalent in Olympic athletes.

### [5] Top 10 Sports by Total Medals
   - This chart identifies the sports with the highest medal totals, offering insights into which sports have been most successful or popular.

### [6] Athletes by Age
   - The distribution of athletes by age provides insights into the typical age range for Olympic competitors, which can vary by sport.

### [7] Athletes by Weight
   - The weight distribution chart highlights the variation in athlete weights, which may correlate with specific sports or events.

### [8] Athletes by Height
   - The height distribution of athletes provides insights into the physical attributes common among Olympic athletes, potentially linked to their sports.
