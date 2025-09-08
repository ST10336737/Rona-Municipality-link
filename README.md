# Rona-Municipality-link System
![Road_puds](https://github.com/user-attachments/assets/6573518c-5299-4038-acfa-d618bca3b561)

## Brief
 The MVC (Model-View-Controller) architecture was used in the development of this C# Windows Forms application in Visual Studio.
 Residents can easily report problems to their municipality using the program that is inclusive and allows transparency from the user.
 Only the Report Issues feature is operational at the moment which enables users to Upload media,input location,the brief description of issue.  Until further upgrades, the other options—Local Events & Announcements and Service Request Status—are visible but inactive.

 # Features Accomplished/Implemented 
## Main Menu with three tasks:

-- Report Issues (implemented)

-- Local Events & Announcements (disabled)

-- Service Request Status (disabled)

## Report Issues Form includes:

-- Location input (Textbox)

-- Category selection (Dropdown/ListBox)

-- Detailed description (RichTextBox)

-- File attachment for images/documents (OpenFileDialog)

-- Submit button to save report

-- Engagement feature (Label/ProgressBar with encouraging feedback)

-- Navigation button to return to main menu

# Technical Details

Language: C#

Framework: .NET (Windows Forms Application)

Architecture: MVC (Model-View-Controller)

Data Structures: Reports are stored in memory using a List<IssueReport> where IssueReport is a model class containing:

Location (string)

Category (enum/string)

Description (string)

Attachment path (string)

Timestamp (DateTime)
