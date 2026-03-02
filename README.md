Aconex-Aligned Document Control Dashboard 🏗️📊

Project Overview

This project showcases a sophisticated Document Control & MIS Reporting System specifically designed for large-scale construction metadata management. It demonstrates the transition from manual, error-prone tracking to an automated, single-click update system using real-world Aconex metadata structures.

The Problem

Managing document lifecycles in high-budget construction projects often involves thousands of entries (Drawings, RFIs, Submittals). The primary challenges addressed here are:

Manual Reporting Latency: Traditional methods of updating status logs manually take hours of administrative effort.

Version Control Risks: High probability of error in tracking the latest document revisions.

Bottleneck Identification: Difficulty in visualizing which discipline (Civil, Electrical, etc.) or reviewer is holding up the approval process.

The Solution

I engineered a dynamic reporting solution that acts as a bridge between Aconex exports and Executive Decision-Making.

ETL Process: Leveraged Power Query to extract, transform, and load disjointed document logs from CSV/Excel exports.

Data Cleaning: Standardized dates, handled null values in 'Approved Date', and normalized discipline names.

Automated Calculations: Created custom columns to calculate 'Days Overdue' and 'Approval Status' dynamically.

Key Features

Executive Dashboard: A visual summary showing Total Documents, Pending Approvals, and Overdue counts.

Aging Analysis: Identifies how many days a document has been sitting in the 'Pending' state.

Discipline Distribution: Pivot-based breakdown for Architectural, Civil, Electrical, Mechanical, and Plumbing disciplines.

One-Click Refresh: The entire reporting engine updates instantly when a new Aconex data export is added to the source folder.

Tech Stack

Advanced Excel: Power Query, Pivot Tables, Dashboard Layout Design.

SQL: Used for initial data validation and mock-database querying.

Domain Expertise: Aconex Workflow Management, Document Revision Control (PCI Standards).

Project Structure

/Data_Source: Contains sanitized sample CSV/XLSX files used for the analysis.

/Documentation: A PDF guide explaining the Power Query steps and logic.

/Screenshots: High-resolution images of the final Dashboard UI.

About the Author

Inamul Hasan
Reporting Analyst | MIS Specialist | Google Certified Data Professional

I specialize in automating reporting workflows and maintaining 100% data integrity in complex environments.

🔗 linkedin.com/in/inam-hasan
📧 inam.hasan@outlook.com


