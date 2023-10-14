---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Data Engineer
    company: Curri
    company_url: 'https://www.curri.com/'
    company_logo: org-gc
    location: California
    date_start: '2023-02-01'
    date_end: ''
    description: |2-
        * Create end to end production level data pipelines and innovate KPIs relevant to business problems.
        * Helped create an analytics data warehouse by transforming data (dbt) to define business logic and democratize analytics across the entire company.
        * Create centralized dashboards making it easy for the entire company to understand the health of the business and non-technical users to answer their own questions.

  - title: Junior Data Engineer
    company: Curri
    company_url: 'https://www.curri.com/'
    company_logo: org-gc
    location: California
    date_start: '2021-06-01'
    date_end: '2023-02-01'
    description: |2-
        * Deployed GPT application to summarize sales phone calls. Summaries were ETL'd into a data warehouse and posted in Slack. Additionally built an interactive data viewer to help the "C Suite" digest all of the important summarized customer interaction for the day.
        * Put together automated reporting for venture capital investors including cohort and churn analysis
        * Built and tested predictive models locally (Scikit Learn), then deployed an endpoint through AWS (Sagemaker). Predictive model eliminated the manual work required to get customers a quote, leading to increased customer bookings, improved operational efficiency, and a better customer experience

design:
  columns: '1'
---
