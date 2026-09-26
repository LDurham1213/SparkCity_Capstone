# New York Digital City

### SparkCity Capstone Project

<p align="center">
  <img src="docs/images/sparkcity-capstone.png" alt="New York Digital City Dashboard" width="90%">
</p>

**My Role:** Project Manager • Application Design • Mobility & Traffic Development

---

## Project Overview

**New York Digital City** is an interactive city-planning and convention
analytics dashboard developed by a six-person team as our final capstone project
at **Zip Code Wilmington**.

Working within an **11-day development window**, our team transformed the
original SparkCity smart-city data engineering foundation into a decision-support
application designed to answer a practical question:

> **What would be the impact of bringing a major convention to New York Digital City?**

The application brings together traffic, environmental, infrastructure,
occupancy, energy, and fiscal data to help planners evaluate when to hold a
large convention and understand its potential impact on the city.

The final application provides a unified planning experience across six primary
areas:

- Overview
- Convention Planner
- Mobility & Traffic
- Environment
- Capacity & Infrastructure
- Fiscal Impact

The team's final analysis centered on a proposed convention window of
**November 3–5, 2027**.

---

## The Challenge

Planning a large convention requires more than selecting an available date.

City planners need to consider multiple factors at the same time, including:

- Traffic volume and congestion
- Transportation conditions
- Environmental conditions
- Hotel and occupancy capacity
- Energy and infrastructure demand
- Visitor spending
- City expenses and revenue
- Overall fiscal impact

These factors existed across separate datasets and analytical domains.

Our challenge was to transform those datasets into a single application that
would allow planners to evaluate the city as a connected system rather than
reviewing each dataset independently.

---

## The Solution

New York Digital City combines data engineering, analytics, and interactive
visualization into a unified convention-planning dashboard.

The application allows users to explore historical city conditions, review a
recommended convention window, compare planning factors, and examine potential
impacts across multiple operational areas.

The solution combines:

- Historical data analysis
- PostgreSQL data storage
- Python-based analytics
- PySpark data workflows
- Interactive Streamlit dashboards
- Plotly visualizations
- Convention scenario modeling
- Data validation
- Automated testing
- Responsive dashboard design

---

# Dashboard Areas

## Overview

The Overview page provides an executive-level summary of the convention
planning analysis.

It highlights:

- Recommended convention period
- Alternative planning options
- Convention suitability information
- Key city indicators
- Planning insights
- Navigation to each analytical domain

The original application design and visual concept were created by **Leigh**,
with the Overview / Landing Page implementation developed by **Vijay**.

---

## Convention Planner

The Convention Planner brings multiple planning factors together to evaluate
potential convention periods.

Users can explore planning considerations and compare factors that influence
the overall recommendation.

The planner presents:

- Suitability information
- Factor-level analysis
- Recommended planning window
- Alternative planning window
- Key planning takeaways
- Month-by-month comparisons

The team's final convention scenario focused on **November 3–5, 2027**.

---

## Mobility & Traffic

The Mobility & Traffic dashboard evaluates transportation conditions
surrounding the proposed convention period.

The analysis examines approximately **110,000 traffic records** and explores:

- Vehicle volume
- Average traffic speed
- Congestion levels
- Road-type patterns
- Peak traffic periods
- Historical weekday traffic behavior
- Potential convention-related transportation impact

Historical **November Wednesday–Friday traffic patterns** provide context for
understanding conditions surrounding the proposed Wednesday–Friday convention
window.

The dashboard translates traffic data into planning insights and transportation
recommendations that can be used when evaluating the proposed event.

---

## Environment

The Environment dashboard evaluates environmental conditions that may influence
convention planning.

Analysis includes:

- Historical weather
- Temperature
- Precipitation
- Air quality
- Environmental planning considerations
- Historical conditions surrounding the proposed convention period

Historical environmental data provides additional planning context for the
November convention window.

---

## Capacity & Infrastructure

The Capacity & Infrastructure dashboard evaluates whether city resources can
support increased visitor demand.

Analysis includes factors such as:

- Occupancy
- Available capacity
- Infrastructure utilization
- Energy demand
- City resource considerations

This domain helps planners evaluate whether the city has sufficient capacity
to support a major event while considering the demands placed on existing
resources.

---

## Fiscal Impact

The Fiscal Impact dashboard examines the potential financial implications of
hosting a major convention.

The analysis considers:

- Visitor spending
- Revenue
- Expenses
- Hotel occupancy
- Seasonal fiscal patterns
- Estimated event-related costs
- Potential net fiscal impact

Interactive controls allow planners to explore how changes in factors such as
attendance, duration, timing, and planning assumptions affect projected
financial outcomes.

---

# My Contributions

## Project Manager, Application Designer & Mobility / Traffic Developer

I served as the **Project Manager for our six-person development team**, guiding
the project from initial planning and application design through development,
integration, testing, and final presentation.

I also created the **original application design and visual direction**,
establishing the foundation for the dashboard's overall layout, user experience,
and presentation. Team members then implemented their assigned analytical
domains within the shared application.

In addition to project leadership and design, I maintained hands-on technical
ownership of the **Mobility & Traffic** domain.

---

### Project Management & Team Leadership

As Project Manager, I worked across all aspects of the project, including:

- Organizing work across the six dashboard domains
- Establishing project priorities
- Coordinating development activities
- Tracking tasks, dependencies, and overall project progress
- Facilitating team discussions and decision-making
- Coordinating work between independently developed application areas
- Managing final application integration
- Reviewing application consistency across dashboard areas
- Coordinating testing and regression testing
- Supporting Git/GitHub branch and pull request workflows
- Identifying and helping resolve integration issues
- Coordinating final application readiness
- Organizing the team's demo flow and presentation
- Keeping the team focused on delivering the completed application within the
  11-day development window

---

### Application Design & User Experience

I created the **original application design and dashboard concept** that
provided the visual foundation for New York Digital City.

My design contributions included:

- Establishing the original dashboard layout and visual direction
- Designing the initial application experience and page structure
- Defining how information should be organized and presented
- Establishing the visual foundation used across the application
- Reviewing team-developed pages for consistency
- Refining layouts, spacing, typography, and responsive behavior
- Helping create a cohesive experience across independently developed
  dashboard areas

The individual dashboard areas were implemented collaboratively by the team,
with developers responsible for coding their assigned domains.

---

### Mobility & Traffic Development

I had direct technical ownership of the **Mobility & Traffic** dashboard.

My work included:

- Analyzing approximately 110,000 traffic records
- Evaluating vehicle volume, average speed, and congestion patterns
- Analyzing traffic behavior by road type
- Identifying peak traffic periods
- Developing historical November weekday comparisons
- Evaluating the potential traffic impact of the proposed convention
- Translating traffic analysis into actionable planning insights
- Building interactive dashboard visualizations
- Developing transportation recommendations for convention planners
- Refining dashboard layout and responsive behavior

---

### Application Integration & Quality

I worked across the completed application to help bring the team's independently
developed components together into a cohesive final product.

This included:

- Integrating team-developed features
- Reviewing and merging team changes
- Synchronizing convention dates and assumptions across pages
- Standardizing terminology and presentation
- Supporting responsive design and UI consistency
- Creating and coordinating unit and integration testing tasks
- Running regression tests against the integrated application
- Troubleshooting issues introduced during integration
- Supporting final release readiness

The final integrated application completed the automated test suite with:

```text
132 passed
11 skipped
0 failed
```

Serving simultaneously as **Project Manager, application designer, and
contributing developer** required balancing project leadership, product
direction, and hands-on technical delivery.

The experience strengthened my ability to lead a development team, translate an
initial concept into an implemented product, coordinate technical dependencies,
integrate independently developed components, resolve technical issues, and
guide a project from design through delivery under a compressed development
schedule.

---

# Data

The application works with seven primary smart-city data domains:

| Dataset | Purpose |
|---|---|
| Traffic Sensors | Vehicle volume, speed, congestion, and road conditions |
| Air Quality | PM2.5, PM10, NO2, CO, temperature, and humidity |
| Weather | Temperature, precipitation, wind, humidity, and pressure |
| Energy Meters | Power consumption and electrical measurements |
| City Zones | Geographic and city-zone reference information |
| Occupancy | Available rooms, occupied rooms, and guest activity |
| Fiscal Data | Revenue and expense information |

The project supports multiple source-data formats, including:

- CSV
- JSON
- Parquet

Data validation and transformation utilities are implemented through the
shared `sparkcityx` Python package.

---

# Technical Architecture

New York Digital City combines a shared data layer with independently developed
analytical dashboard domains.

```text
Smart City Data Sources
        │
        ▼
Data Ingestion & Validation
        │
        ▼
PySpark / Python Processing
        │
        ▼
PostgreSQL
        │
        ▼
Shared Analytics & Planning Logic
        │
        ▼
Streamlit Application
        │
        ├── Overview
        ├── Convention Planner
        ├── Mobility & Traffic
        ├── Environment
        ├── Capacity & Infrastructure
        └── Fiscal Impact
```

The shared architecture allowed team members to work independently on assigned
analytical domains while integrating each page into a common application.

---

# Tech Stack

## Languages & Analytics

- Python
- SQL
- PySpark
- Pandas

## Application & Visualization

- Streamlit
- Plotly
- PyDeck
- HTML/CSS

## Data

- PostgreSQL
- Psycopg
- CSV
- JSON
- Parquet

## Development & Infrastructure

- Git
- GitHub
- Docker
- Docker Compose
- `uv`
- Pytest

---

# PostgreSQL Integration

The application uses PostgreSQL as the team's shared relational data store.

Application code uses a shared database helper rather than embedding
credentials directly in application code.

```python
from sparkcityx.database import connect_database

with connect_database() as connection:
    with connection.cursor() as cursor:
        cursor.execute("SELECT 1")
        assert cursor.fetchone() == (1,)
```

`connect_database` reads the `DATABASE_URL` from the process environment.

Database credentials are supplied through environment configuration and are
not committed to the repository.

The database connection requires an encrypted SSL mode.

---

# Data Loading & Validation

The project includes reusable utilities for loading and validating the primary
datasets.

Supported validation domains include:

- Traffic
- Air quality
- Weather
- Energy
- City zones
- Occupancy
- Fiscal data

Validation operates on PySpark DataFrames and is separated from file-loading
and database operations.

Example:

```python
from sparkcityx.data_quality import get_validation_config, validate_dataframe
from sparkcityx.loaders import load_dataset

traffic_df = load_dataset(
    spark,
    "data/reference/traffic_sensors.csv"
)

report = validate_dataframe(
    traffic_df,
    "traffic"
)

print(report["valid"], report["record_count"])
```

The shared loader supports:

- CSV
- Parquet
- JSON arrays
- Newline-delimited JSON

---

# Testing

Testing was an important part of the development and final integration process.

The project includes automated tests covering application logic, data handling,
dashboard behavior, and integration-related functionality.

The final integrated build completed the full automated test suite with:

```text
132 passed
11 skipped
0 failed
```

Automated testing was supplemented by manual regression testing of the
integrated dashboard before final delivery.

---

# Development Workflow

The six-person team used a branch-based Git/GitHub development workflow.

```text
Individual / Feature Branch
            │
            ▼
        Pull Request
            │
            ▼
            dev
            │
      Integration Testing
            │
            ▼
           main
```

Team members developed their assigned dashboard areas independently and
submitted completed work through pull requests.

During final integration, the team:

1. Merged completed feature branches into `dev`
2. Synchronized convention dates and planning assumptions
3. Reviewed dashboard styling and terminology
4. Resolved integration issues
5. Ran automated tests
6. Performed manual regression testing
7. Promoted the completed application for final presentation

This workflow allowed six developers to work concurrently while maintaining a
shared integration branch.

---

# Team

New York Digital City was developed by a **six-person team** as the final
capstone project for the **Zip Code Wilmington Data Engineering Program**.

| Team Member | Role / Primary Responsibility |
|---|---|
| **Leigh** | **Project Manager, Application Design & Mobility / Traffic Development** |
| Vijay | Overview / Landing Page Development |
| Monah | **Scrum Master, Convention Planner |
| Matt | Environment |
| Sloane | Capacity & Infrastructure |
| Hakeem | Fiscal Impact |

While each developer had primary ownership of an analytical domain, development,
integration, testing, and final delivery required collaboration across the team.

---

# Running the Application Locally

For complete local installation and database configuration instructions, see
the repository's setup documentation.

## Standard Python Setup

Install `uv` and a Java runtime supported by Spark. Java 17 or 21 is
recommended.

From the repository root:

```bash
uv python install 3.13
uv sync --dev
```

Run the automated tests:

```bash
uv run pytest
```

---

## Database Configuration

Copy `.env.example` to:

```text
secrets/.env
```

Replace the placeholders with the appropriate database credentials.

> **Important:** Environment files containing database credentials must not be
> committed to GitHub.

Verify the database connection without modifying application data:

```bash
uv run python scripts/check-database.py
```

---

## Database Schema

Preview the additive schema migration:

```bash
uv run python scripts/setup-database.py
```

After review, apply the schema:

```bash
uv run python scripts/setup-database.py --apply
```

Inspect the database:

```bash
uv run python scripts/inspect-database.py
```

The migration creates the `sparkcity` schema and seven application tables.

---

## Loading Data

Dataset owners can preview and load individual datasets.

Example using traffic data:

```bash
uv run python scripts/load-dataset.py traffic
```

Apply the load:

```bash
uv run python scripts/load-dataset.py traffic --apply
```

The loader validates the PySpark DataFrame before opening the database
transaction and preserves existing records when the load is repeated.

---

## Start the Dashboard

The dashboard entry point is located at:

```text
dashboard/app.py
```

Use the repository's setup documentation for the current environment-specific
startup command and database configuration.

---

# Security & Configuration

Sensitive configuration is managed through environment variables rather than
being embedded in application code.

The PostgreSQL connection helper requires an encrypted SSL mode and rejects
insecure connection modes.

Database credentials and local environment files should never be committed to
source control.

---

# Project Evolution

SparkCity began as a smart-city IoT data engineering foundation focused on
PySpark, sensor data, data quality, and PostgreSQL.

For our final capstone, the six-person team transformed that foundation into
**New York Digital City** — an integrated convention-planning and city-impact
analytics application.

The final project expanded the original data engineering foundation by
introducing:

- A unified multi-page analytical dashboard
- Convention suitability analysis
- Cross-domain planning recommendations
- Traffic impact analysis
- Environmental planning analysis
- Capacity and infrastructure analysis
- Fiscal impact modeling
- Shared application design and navigation
- Responsive dashboard behavior
- Automated testing
- Team-based integration and release workflows

The result was a working decision-support application designed and developed
within an **11-day capstone window**.

---

# Key Takeaways

New York Digital City demonstrated how multiple data domains can be brought
together to support a single planning decision.

From a development perspective, the project required more than building
individual dashboard pages. Six developers had to coordinate data assumptions,
application architecture, visual design, testing, Git workflows, integration,
and presentation under a compressed delivery schedule.

As **Project Manager, application designer, and Mobility & Traffic developer**,
the project brought together several areas of my experience:

- Project leadership
- Team coordination
- Application and UX design
- Data analysis
- Python development
- PySpark
- SQL and PostgreSQL
- Data visualization
- Application development
- Unit and integration testing
- Git/GitHub collaboration
- Application integration
- Responsive UI design
- Technical communication
- Presentation and delivery

The project reinforced the importance of not only building technically sound
solutions, but also coordinating people, technology, data, and design to deliver
a product that decision-makers can actually use.

---

# Project Status

### Completed Capstone Project

New York Digital City was completed as the final team capstone for the
**Zip Code Wilmington Data Engineering Program**.

The repository is maintained as part of my data engineering, application
development, and technical leadership portfolio.
