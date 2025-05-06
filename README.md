# PostgreSQL Job Application Tracker

![Database Schema](docs/schema.png)

A normalized PostgreSQL database for tracking job applications, interviews, and contacts. Perfect for job seekers to organize their search.

## Features

- **Relational Design**: 6 properly normalized tables
- **Realistic Sample Data**: 10000+ records generated with Mockaroo
- **Analytical Queries**: Ready-to-run business insights


## Tech Stack

- **Database**: PostgreSQL 15
- **Data Generation**: Mockaroo
- **Diagramming**: DBML

## Schema Overview

| Table                | Description                          |
|----------------------|--------------------------------------|
| `companies`          | Employer information                 |
| `job_postings`       | Open positions                       |
| `contacts`           | Recruiters/Hiring managers           |
| `application_status` | Lookup table for statuses            |
| `applications`       | Your submitted applications          |
| `interviews`        | Scheduled interviews                 |

