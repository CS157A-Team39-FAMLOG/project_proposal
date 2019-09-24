## Project Proposal

# -FAMLOG-
&nbsp;

&nbsp;

&nbsp;

CS157A - Section 01

Team 39

&nbsp;

&nbsp;

*Benjamin Wen Shen Lee*

*Grace To*

*Jeffrey Nguyen*

&nbsp;

&nbsp;

&nbsp;

# Project Overview
&nbsp;

For our project, we are building an application that will allow households to maintain a centralized shopping list based upon the aggregated, separate lists created by the individuals. The database will store a list for every household, while also storing the distinct lists of each user within that household. Within the database system, the individual lists will contain the items, the quantity of those items, the priority level of the item, and notes for each item. The stored household list will have the household users names and all household list items ordered in descending priority, the priority level of the item, and the notes for each item. In addition, the database will also hold a record system which will log who bought the items as well as the cost of those items. This allows for repayment should someone other than the requester buy those items for the requester. The main stakeholders are all the households with two members or greater. This application is significant in its approach in the delegation of shopping when time is not optimal. When one individual may already be shopping, he or she will have the ability to buy someone else’s items that are on the household master list.

&emsp;

# System Environment
&nbsp;

![3-tier diagram](https://github.com/CS157A-Team39-FAMLOG/project_proposal/blob/master/structured_diagram1.png)

                                      Structured diagram of the 3-tier architecture
&emsp;

# Functional Requirements
&nbsp;

###  *About Users*
  - The application focuses on each household as a target
  - Each household may have two to multiple users
###  *Functionality*
  - User first creates account for the household, this account will be added to the database
  - Table will be created for Users
  - User signs in to access the system
  - User has to enter their name in order to access the data system, add this user to that account and the database if this name does not exist
  - User then chooses to access between personal list and master list
  - In the personal list, user can add his/her wanted items into the shopping list, items get added to database
  - User can also edit his/her items in their own shopping list (remove items/edit notes/edit name), and the database will be updated
  - In the master list, user can see the total shopping items of everyone in the house in descending priority order
  - Users’ names will appear beside their personal listed items in the master list
  - In the master list, the person who purchased the items can select and enter the price they bought the items for
  - The application will calculate the total price of the items bought (the selected items will be automatically removed from the list)
  - User can log out of the system
  
&emsp;

# Non-functional Issues
&nbsp;

We plan to use Adobe XD to design the website interface and Adobe Photoshop to create necessary graphics. Our website should be available 24/7 on any browser, as long as users have access to the internet, and have also made an account for their household. For more enhanced security, we might implement a passcode system for the users within an account, to make sure there is no misuse among users. Users of different accounts should be able to access our website simultaneously without any interruptions while the other users are online.

