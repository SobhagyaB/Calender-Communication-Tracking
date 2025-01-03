#  ENTNT Technical Assignment : Calendar Application for Communication Tracking

Objective

Our goal is to foster effective professional relationships by maintaining precise records of our communications with other organizations. 
This task involves building a React-based Calendar Application to streamline communication tracking, ensuring timely follow-ups and consistent engagement. 
The platform will centralize interaction history, facilitate future communication planning, and optimize engagement schedules based on preset intervals.

Application Overview

The application will include:

Admin Panel: For setting up organizational details and communication parameters.

User Interface: For managing communication tasks and schedules.

Analytics and Reporting Module (optional): For generating actionable insights.

The design should prioritize user-friendliness, clarity, and efficient data management.

Detailed Specifications

Admin Panel

This module will allow administrators to configure and manage core application data.

Company Management

Admins can perform the following operations for managing companies:

Add, Edit, and Remove Company Details, including:

Name: Company’s official name.

Location: Operational or physical location.

LinkedIn URL: Link to the company’s LinkedIn profile.

Email Addresses: One or more communication emails.

Contact Numbers: Representative phone numbers.

Notes: Additional comments or observations.

Communication Frequency: Default interval for scheduling interactions (e.g., bi-weekly).

Communication Method Configuration

Admins can define and manage communication methods, specifying:

Title: E.g., "In-person Visit" or "Email."

Details: Description of the method, such as "Send an introductory email."

Order: Determines the sequence in which methods are used (e.g., Social Media Post > Email > Phone Call).

Mandatory Indicator: Specifies if the method is required in the communication sequence.

Default methods include:

Social Media Post

Direct Message

Email

Phone Call

Other Methods

User Interface

This module serves as the primary workspace for users to visualize, manage, and execute communication tasks.

Dashboard

The dashboard displays a grid view with the following information:

Company Name: Name of the organization.

Recent Communications: Summary of the last five interactions, including the type and date (e.g., "Social Media Post - Sept 5").

Next Scheduled Interaction: Planned method and date of the upcoming communication.

Status Indicators:

Red Highlight: Overdue interactions.

Yellow Highlight: Communications due today.

Customizable: Users can disable or modify highlights for specific entries.

Interactive Features

Hover Effects: Display additional notes for completed communications on hover.

Communication Logging:

Users can select one or multiple companies.

Use a "Log Communication" button to record new interactions:

Choose the type of interaction (e.g., Social Media Post, Phone Call).

Specify the interaction date.

Add comments or observations.

Logging resets overdue or due status highlights.

Notifications

A dedicated notifications section includes:

Overdue Communications: List of companies with missed interactions.

Today’s Tasks: List of scheduled communications for the day.

Notification Badge: Displays the total count of overdue and due tasks.

Calendar View

A calendar interface enables users to:

Review past interactions with details of dates and methods.

Manage future communications by viewing and updating scheduled tasks.

Analytics and Reporting Module (Optional)

This section provides insights into communication trends and effectiveness.

Features

Communication Frequency Report:

Visual charts (e.g., bar or pie charts) displaying the usage frequency of various communication methods over a specific period.

Filters for company, date range, or interaction type.

Engagement Effectiveness Metrics:

Analyze which methods yield the highest responses or follow-ups.

Display metrics like success rates of emails, phone calls, or social media messages.

Overdue Trends Analysis:

Use trendlines or heatmaps to show overdue interaction patterns over time, categorized by company.

Exportable Reports:

Enable downloads in PDF or CSV formats for offline review or sharing.

Live Activity Feed:

A real-time log of all communication actions performed, sortable by date, user, or company.
