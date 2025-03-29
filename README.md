
# Nest

The app is to be developed to address these issues by providing an automated solution for categorizing, and managing events such as meetings etc, ultimately enhancing productivity and reducing the burden of manual calendar management.


![alt text](https://scontent.fceb3-1.fna.fbcdn.net/v/t1.15752-9/484347644_636094109577743_2356054137514033287_n.png?stp=dst-png_s2048x2048&_nc_cat=105&ccb=1-7&_nc_sid=9f807c&_nc_ohc=b9QSiRGIn3MQ7kNvgHrx-yT&_nc_oc=AdlI0vht1UCqZWgNTLCo9DksNDnAPXps4Vyv0ZhYefwhtfCXg1CW3wraqiXGqcK0Qlo&_nc_zt=23&_nc_ht=scontent.fceb3-1.fna&oh=03_Q7cD1wE2EZai9pv81gEsMJU_7SOvvihOQRoPBC3K36LYGXyNyA&oe=680F37FC)

![alt text](https://scontent.fceb3-1.fna.fbcdn.net/v/t1.15752-9/483530711_1656712735237050_8151890706811541776_n.png?stp=dst-png_s2048x2048&_nc_cat=110&ccb=1-7&_nc_sid=9f807c&_nc_ohc=uowtHRcgVcoQ7kNvgHNGuya&_nc_oc=AdmC_WL1ektAI3dG0K8d1v0RX7V5i-Q-k3z78_illw2qfvsGst3giRsYZVTGcLFgY7g&_nc_zt=23&_nc_ht=scontent.fceb3-1.fna&oh=03_Q7cD1wHA1wqSRegkPvfYxyVKXs2AcQKyW1TfjLV4YlSqc_F_iA&oe=680F12ED)

# Functional Requirements

## Authentication / Login and Registration

The system must allow users to register, log in, and authenticate securely.

- Password Complexity: Users must create strong passwords that include a mix of uppercase letters, lowercase letters, numbers, and special characters.
- Error Handling: Provide user-friendly error messages for scenarios like invalid login attempts, registration failures, and password mismatches.
- Session Management: Implement secure session handling using token-based authentication. Features like session expiration and logout options ensure security.
- Database Support: Use relational (MySQL, PostgreSQL) or non-relational (MongoDB) databases for authentication, with Django handling the server-side logic.

## Link Organizer

Users can manage their external links (e.g., scheduled meetings) using the following features:

- Add Links: Users can add new links with details such as the name, URL, and a description.
- Edit Links: Users can modify existing link details.
- Delete Links: Users can remove links they no longer need.
- View Links: Display saved links in a list, with sorting and filtering options.
- Categorization: Users can organize links into predefined or custom categories for better management.

## Categorization

Users can categorize data and content with the following capabilities:

- Predefined and Custom Categories: Choose from predefined categories or create custom ones for better organization.
- Tagging and Filtering: Assign tags to items and filter content by category, tag, or other attributes.

## Parsing Events

The system automatically parses scheduled links into organized, easy-to-view events, helping users manage tasks and deadlines more efficiently.



# Optional Features

## Automated Schedule Gap Identification and Task Assignment

Enhance productivity with automated gap detection and task assignment.

- Gap Detection: Analyze work, school, or event schedules to identify free time within a 24-hour period.
- Task Assignment: Automatically suggest or assign tasks to available time slots.
- Recursive Scheduling: Apply gap detection and task assignment over a week or a month.

## Notifications / Reminders

Allow users to set notifications or reminders for upcoming tasks, events, or schedule changes.

## Time Estimation for Tasks

Enable users to estimate the duration of tasks. The scheduler will automatically adjust available time slots based on these estimates.

## Priority-Based Scheduling

Allow users to assign priority levels to tasks or events, ensuring high-priority items are scheduled first.

## Recurring Tasks and Events

Support recurring scheduling for tasks or events (daily, weekly, or monthly) to automate repetitive tasks.
# GANTT CHART

https://docs.google.com/spreadsheets/d/1DDcX2QFPq0fwrB0ADPTwiGHagGypi_Tlt7m-oKX9lXc/edit?usp=sharing

# ERD

https://lucid.app/lucidchart/5ffb15d8-721d-4da4-8d53-179f8a59e261/edit?viewport_loc=333%2C-1641%2C2647%2C1520%2C0_0&invitationId=inv_51865532-232e-47c5-9b57-4f572c34bb95

# UI/ UX DESIGN

https://www.figma.com/design/J7ee0FpgF2qD2yIp5FqTzj/Information-Management-2-(UI-%2F-UX-)?node-id=0-1&t=8sXbcibwYCDYRl6m-1

