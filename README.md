# Codecademy Learners Mockup Data

## Project Overview
<p>This project involves analyzing mockup Codecademy learner data from two tables: users and progress. <br>
The users table contains information about learners, including user_id, email_domain, country, postal, mobile_app, and sign_up_at. <br>
The progress table tracks the progress of learners in various programming languages.</p>

## Tables
<b>users table</b>
1. <b>user_id:</b> Unique identifier for each user.
2. <b>email_domain:</b> Email domain of the user.
3. <b>country:</b> User's country.
4. <b>postal:,/b> User's postal code.
5. <b>mobile_app:</b> Indicates whether the user uses the mobile app (true/false).
6. <b>sign_up_at:</b> Date and time when the user signed up.
   
<b>progress table :</b>
1. <b>user_id:</b> Unique identifier linking to the users table.
2. <b>learn_cpp:</b> Progress in learning C++.
3. <b>learn_sql:</b> Progress in learning SQL.
4. <b>learn_html:</b> Progress in learning HTML.
5. <b>learn_javascript:</b> Progress in learning JavaScript.
6. <b>learn_java:</b> Progress in learning Java.
   
## Setup Instructions:
If learners opt to work on this project outside of Codecademy, they can download the necessary files. The setup process involves using SQLite and running SQL commands from a terminal or using DB Browser, a desktop application. Detailed instructions are provided in the SQLite setup guide and the article on running SQL commands in DB Browser.

## Tasks:
1. Top 25 Schools (.edu Domains)
   + Identify the top 25 schools based on .edu email domains.
3. .edu Learners in New York
   + Determine the number of .edu learners located in New York.
5. Mobile App Users
   + Count the number of Codecademy learners using the mobile app.
7. Sign-Up Counts by Hour
   + Query sign-up counts for each hour using the strftime() function.
9. Analysis by Joining Tables
    + Explore insights by joining the users and progress tables:
        + Analyze course preferences of different schools with .edu domains.
        + Identify courses taken by learners from New York.
        + Determine courses taken by learners from Chicago.




