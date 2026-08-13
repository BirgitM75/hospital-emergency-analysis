# Emergency Department Analysis

## Project Overview
This data-driven project analyses logistical bottlenecks and patient waiting times in the emergency department of the fictional "Klinikum Nord-Süd." The goal is to identify patterns in patient volume (e.g., weekend night shifts) and develop strategic recommendations to relieve staff pressure and improve patient safety.

## Dataset Structure
The project is built on a relational data model consisting of three core areas:
* **patienten.csv:** Patient master data (age, insurance status, postal code prefix).
* **aufnahmen.csv:** Emergency department admission data, including triage levels (Manchester Triage System 1–5) and precise timestamps for arrival and doctor contact.
* **behandlungskosten.csv:** Cost overview and types of medical treatments (laboratory, CT scan, X-ray).

## Planned Analytical Steps
1. **SQL:** Table joining via relational keys and mathematical calculation of actual patient waiting times in minutes using `DATEDIFF`.
2. **Tableau:** Visual processing of waiting times by shifts and weekdays, alongside an analysis of non-urgent cases (Triage 4 & 5).
3. **Strategy:** Development of a structured, data-backed action plan involving a "geo-fenced" portal clinic concept and shift-schedule optimization.

Created as initial exercise as part of the Data Analytics Course | WBS Coding School | August 2026*

