# Instagram Clone Data Science Project

## Project Overview

This project simulates an Instagram clone to analyze user interactions, content engagement, and network relationships. The project involves creating a database in MySQL Workbench, transferring the data to Excel for further manipulation, and ultimately generating a comprehensive 6-page dashboard report that visualizes key insights.

## Project Files

- **SQL Scripts:**
  - `Insta Database Creation.sql`: Script to create the Instagram clone database.

- **Excel File:**
  - `Insta Clone.xlsx`: Excel file containing the exported data and dashboard.

- **Dashboard:**
  - `InstaSights Dashboard.pbix`: Final dashboard report on Power BI.
  - `Power BI Report.pdf`: PDF of the dashboard.

## Project Structure

1. **Database Design and Creation:**
   - **Tool:** MySQL Workbench
   - **Tables:**
     - **user:** Contains user information including user_id, username, email, etc.
     - **posts:** Stores data about posts including post_id, user_id, content, timestamp, etc.
     - **comment:** Tracks comments made on posts, including comment_id, post_id, user_id, content, timestamp, etc.
     - **followers:** Logs the relationship between followers and the followed, including follower_id, followed_id, etc.
     - **followed:** Similar to followers but focuses on users being followed.
     - **tags:** Records tags associated with posts, including tag_id, post_id, tag_name, etc.

2. **Data Export and Manipulation:**
   - **Tool:** Microsoft Excel
   - **Process:** Data from the MySQL Workbench database is exported to Excel sheets. The data is then organized, cleaned, and structured to prepare for dashboard creation.

3. **Dashboard Creation:**
   - **Tool:** Power BI
   - **Content:** A 6-page dashboard report visualizing relationships and insights derived from the data using DAX queries for further column c. Key areas include:
     - User Engagement: Interaction levels of users with posts and comments.
     - Content Analysis: Popularity and reach of posts based on likes, comments, and tags.
     - Network Relationships: Analysis of the follower-following dynamics.
     - Tag Analysis: Trending tags and their impact on content reach.

## Key Features

- **User Analysis:** Detailed insights into user behavior and engagement.
- **Content Trends:** Visualization of trending topics and popular content.
- **Network Analysis:** Examination of social network relationships.
- **Dashboard:** A multi-page interactive report summarizing the findings.
