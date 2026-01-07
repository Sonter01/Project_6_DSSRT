**Disease Symptom Self-Reporting Tool (DSSRT)**

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
**5. Data Flow and Privacy Diagram**
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

**Interpreting Charts:**
 Bar Charts: Identify the most prevalent symptoms.
 Line Graphs: Track changes in reporting volume over time.
 Location Data: Detect clusters of reports for early outbreak signals.

**6. Expected Outcomes**
 Early detection of community-level health trends.
 Increased public participation in disease surveillance.
 Scalable Minimum Viable Product (MVP) for future integration with advanced analytics.

**Conclusion**
The DSSRT project successfully delivers a fully functional prototype application that meets all
key objectives, including complete source code hosted on GitHub, a live deployed application
with both public reporting and secure admin login, a clear data flow and privacy diagram high-
lighting user anonymity, and a comprehensive admin access guide for interpreting aggregated
charts and trends. By combining anonymous reporting, secure data handling, and intuitive
dashboards, DSSRT offers a practical, privacy-focused solution for public health surveillance.
The system provides a strong foundation for proactive disease monitoring and outbreak pre-
vention while remaining lightweight, scalable and community-oriented.

