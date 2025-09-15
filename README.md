# Fitpro-Gym

![Project Image Placeholder](https://github.com/SumanBheemkar/Fitpro-Gym/blob/main/Fitpro_logo.png)

This project reflects how data-driven analysis can directly support business objectives by transforming raw data into actionable insights

Welcome to my SQL project, where I analyze real-world style data from FitPro Gym. The dataset contains 10,000 visit records, and through structured queries, I explore membership trends, demographics, and visit behavior. The goal is to answer key business questions that can help a fitness center better understand its customer base, increase retention, and optimize services.

I bring a business-first perspective to data analytics—connecting insights with real organizational challenges. This project demonstrates how structured data analysis can drive actionable decisions, whether in fitness, HR, or broader business operations.

# Introduction
This project demonstrates essential SQL skills by analyzing a dataset from FitPro Gym. Using SQL, I explored:
Membership details
Member demographics
Visit patterns

The focus is on transforming raw data into insights that answer real business problems. Beyond technical SQL, the project highlights how analytics can align with business strategy.
Project Structure

SQL Scripts – Code for schema creation and analysis queries.
Dataset – Realistic data on gym visits, membership, and demographics.
Analysis – SQL queries addressing business scenarios and performance metrics.

Database Schema
1. Members Table
member_id: Unique identifier for each member
name: Name of the member

2. Memberships Table
member_id: Linked to members table
age: Age of the member
gender: Gender ('M' or 'F')
membership_type: Type (e.g., Monthly, Quarterly)
join_date: Date member joined
status: Membership status (Active, Cancelled)

3. Visits Table
visit_id: Unique visit ID
member_id: Linked to members table
visit_date: Date of visit
check_in_time: Check-in time
check_out_time: Check-out time
Business Problems
The SQL queries aim to solve real business questions:
Retrieve the name and membership_type of female members.

Find members with Monthly memberships who joined after 2023-11-01.
List active members over 25 years.
Get details of visits on a specific date.
Identify Quarterly members aged 20–30.
Aggregations & Grouping
Count visits per member.
Membership count by type (Monthly, Weekly, Quarterly).
Average member age grouped by membership type.
Total visits by date.
Members by status (Active vs Cancelled).

Advanced Queries
Top 3 members with highest visits.
Recently joined active Monthly members.
Members with more than 2 visits (top 5).
Members who joined in 2023, grouped by membership type.

Average age of active members by membership type (top 3).

💡 This project showcases how SQL analysis can support strategic decisions—whether for improving customer experience in a gym, or optimizing workforce retention in HR.
