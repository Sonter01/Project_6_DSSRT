**Introduction:**
Public health surveillance traditionally relies on clinical records, hospital admissions and labo-
ratory testing to track disease spread. While effective, these methods often lag behind real-time
community experiences, leaving gaps in early detection. The Disease Symptom Self-Reporting
Tool (DSSRT) was developed to address this challenge. It is a mobile-friendly web application
that allows individuals to anonymously log daily health check-ins regarding specific symptoms.
The system securely collects subjective symptom data and provides aggregated, anonymized
reports to public health authorities for early trend analysis. The core focus is on creating a user-
friendly, privacy-centric data collection mechanism that aids in community-level surveillance
without collecting personally identifying information.

**1. Problem Statement**
During periods of heightened public health concern, traditional surveillance systems are slow
to capture community-wide trends in subjective symptoms. People often need a clear, trusted
mechanism to report how they feel without fear of revealing personal identity. There is a need
for a lightweight, easily accessible, and privacy-respecting tool to gather real-time, non-clinical
data on symptom prevalence to support preemptive public health interventions.

**2. Source Code**
The complete codebase for DSSRT is hosted on GitHub:
Project 6 DSSRT Repository
Contents of the repository include:
 Frontend: A mobile-friendly React.js application deployed on Vercel.
 Backend: Node.js with Express for secure data handling and anonymization.
 Database: PostgreSQL schema for storing timestamped reports.
 Deployment: Full configuration for Vercel (frontend) and Render (backend and database).

**4. Live Application**
The DSSRT application is deployed and accessible online:
Live DSSRT Application
Features available in the live app:
** Public Reporting Form:**
– Users can anonymously submit symptom check-ins.
– Only symptoms and general location (zip code) are collected.
 Secure Admin Login:
– Authorized health officials can log in to view aggregated reports.
– Dashboard includes charts, trends, and geographic summaries.
5. Data Flow and Privacy Diagram
The DSSRT emphasizes strict privacy and avoids collecting any Personally Identifiable In-
formation (PII).

**Privacy Highlights:**
 No names, emails, IP addresses, or device IDs are collected.
 Only symptom selections and general location (zip code) are stored.
 Reports are aggregated before visualization, ensuring anonymity.

**5. Admin Access Guide**
The DSSRT includes a secure dashboard for public health authorities.
Steps to Access:
1. Click on Admin Dashboard in the top right corner of the application.
2. Enter the password: healthadmin2024
3. Once logged in, the dashboard displays:
 Summary Metrics: Total reports, most common symptoms, and reporting loca-
tions.
 Symptom Prevalence Charts: Bar charts showing frequency of reported symp-
toms.
 Trend Analysis: Line graphs showing daily submission trends.
 Week-Over-Week Trends: Percentage change in symptom reports compared to
the previous period, with visual indicators showing increases or decreases
 Geographic Distribution: Bar charts showing report counts by zip code, displayed
only when a location has at least 10 reports.

Interpreting Charts:
 Bar Charts: Identify the most prevalent symptoms.
 Line Graphs: Track changes in reporting volume over time.
 Location Data: Detect clusters of reports for early outbreak signals.

6. Expected Outcomes
 Early detection of community-level health trends.
 Increased public participation in disease surveillance.
 Scalable Minimum Viable Product (MVP) for future integration with advanced analytics.

Conclusion
The DSSRT project successfully delivers a fully functional prototype application that meets all
key objectives, including complete source code hosted on GitHub, a live deployed application
with both public reporting and secure admin login, a clear data flow and privacy diagram high-
lighting user anonymity, and a comprehensive admin access guide for interpreting aggregated
charts and trends. By combining anonymous reporting, secure data handling, and intuitive
dashboards, DSSRT offers a practical, privacy-focused solution for public health surveillance.
The system provides a strong foundation for proactive disease monitoring and outbreak pre-
vention while remaining lightweight, scalable and community-oriented.


Disease Symptom Self-Reporting Tool (DSSRT)
Overview

Public health surveillance traditionally relies on clinical records, hospital admissions, and laboratory testing to track disease spread. While effective, these methods often lag behind real-time community experiences, leaving gaps in early detection.

The Disease Symptom Self-Reporting Tool (DSSRT) is a mobile-friendly web application designed to allow individuals to anonymously submit daily health check-ins based on experienced symptoms. The system securely collects subjective symptom data and provides aggregated, anonymized reports to public health authorities for early trend analysis.

DSSRT prioritizes privacy, accessibility, and usability, enabling community-level surveillance without collecting any personally identifiable information (PII).

Problem Statement

During periods of increased public health risk, traditional surveillance systems are slow to capture emerging community-wide symptom trends. Individuals often lack a trusted platform to report symptoms anonymously.

There is a need for a lightweight, easily accessible, and privacy-preserving system that gathers real-time, non-clinical symptom data to support early detection and proactive public health interventions.

Source Code

The complete DSSRT codebase is hosted on GitHub.

Repository Structure

Frontend

Mobile-friendly React.js application

Deployed on Vercel

Backend

Node.js with Express

Secure data handling and anonymization

Database

PostgreSQL database

Stores timestamped symptom reports

Deployment

Frontend: Vercel

Backend & Database: Render

Live Application

The DSSRT application is deployed and accessible online.

Features
Public Reporting Form

Anonymous symptom submission

Collects only:

Selected symptoms

General location (ZIP code)

Secure Admin Dashboard

Restricted access for authorized public health officials

Displays aggregated and anonymized data

Includes interactive charts and trend analysis

Data Flow and Privacy

DSSRT is built with a privacy-first architecture and avoids collecting personally identifiable information.

Privacy Highlights

No names, email addresses, IP addresses, or device identifiers are collected

Only symptom selections and general location (ZIP code) are stored

Data is aggregated before visualization to preserve anonymity

Secure backend processing and controlled admin access

Admin Access Guide

The DSSRT includes a secure administrative dashboard for public health authorities.

Access Steps

Click Admin Dashboard at the top-right corner of the application

Enter the password:

healthadmin2024


Access the analytics dashboard

Dashboard Components

Summary Metrics

Total reports submitted

Most frequently reported symptoms

Reporting locations

Symptom Prevalence Charts

Bar charts showing symptom frequencies

Trend Analysis

Line graphs showing daily submission trends

Week-over-Week Trends

Percentage change in symptom reports compared to previous periods

Geographic Distribution

Bar charts of reports by ZIP code

Displayed only when a ZIP code has at least 10 reports

Interpreting the Dashboard

Bar Charts identify the most prevalent symptoms

Line Graphs track reporting trends over time

Geographic Data helps detect symptom clusters for early outbreak signals

Expected Outcomes

Early detection of community-level health trends

Increased public participation in disease surveillance

A scalable Minimum Viable Product (MVP) for future integration with advanced analytics

Conclusion

The Disease Symptom Self-Reporting Tool (DSSRT) delivers a fully functional prototype that meets all core objectives, including a complete open-source codebase, a live deployed application, strict privacy protections, and a comprehensive administrative dashboard.

By combining anonymous symptom reporting, secure data handling, and intuitive visual analytics, DSSRT provides a practical and scalable solution for modern public health surveillance and early outbreak detection.
