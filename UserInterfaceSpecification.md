#  User Management Screen UI Specification

## Introduction
This document outlines the requirements and specifications for the User Management Screen UI. The screen will be used by administrators to manage users within the system.

## Requirements
- The screen should display a list of all users in the system with **their names**, **email addresses**, **roles** and **validity**(enabled or not).
- The list should be **orderable** by username, email address, id, validity(true or false).
- The ID must be **unique for each user** and assigned automatically.
- **Only Administrators** should be able to add new users to the list and order users from the list.
- When adding a user, the administrator should be able to specify the user's **username**, **display name**, **email address**, **phone**, **role** and **validity**.
- The role options should include "**Guest**, "**Admin**" and "**SuperAdmin**".
- The "validity" section should be **checkbox**.
- The screen should have a **clear and intuitive** layout, making it easy for administrators to manage users.


## UI Components
- User List: A table that displays all users in the system, including their usernames, email addresses, id's and validity.
- Sort icon : An icon in the list values that orders users in the list depending on the values that will be ordered
- Hide Disabled User Checkbox: A checkbox for hiding the user whose validity is false.
- New User Button: A button that shows a modal for adding a new user to the system.
- Save User Button: A button that saves the user and user's informations to the list.
- New User Modal: A modal that appears when the New User button is clicked. It includes fields for entering the user's username, display name, phone, email address, user roles and validity checkbox.
- Validity Checkbox: A checkbox which is shown when a new user be saved and it assigns the validity as true if it is checked.
 
## Behavior
- When the User Management Screen is first loaded, the user list should be displayed with all users in the system and should be ordered by ID.
- When the Sort icon is used, the list should be ordered based on the clicked term.
- When the New User Button is clicked, the New User modal should appear, allowing the administrator to enter the user's information.
- When the Save User Button is clicked, the user's information should be submitted to the system.
- When the Hide Disabled User Checkbox is ticked, users should be hiden whose validity are false.

## Conclusion
The User Management Screen should provide administrators with an intuitive and efficient way to manage users within the system. By following the specifications outlined in this document, the screen will meet the requirements and provide a positive user experience.
