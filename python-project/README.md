# Python ETL Project

This project is a simple Python script that demonstrates a basic ETL (Extract, Transform, Load) process.

## What it does

- Extracts data from the GitHub API
- Transforms the JSON response into a simple structure
- Loads (prints) the final output to the console

## Purpose

This is a basic example project created for learning DevOps and data pipeline concepts.  
It is not a production-level system.

## Scheduling

The script is designed to run periodically (for example every 1 hour).

In real-world scenarios, this can be achieved using:

- Cron Jobs (Linux)
- Kubernetes CronJobs
- CI/CD scheduled pipelines (GitHub Actions)

## How to run

Install dependencies:

```bash
pip install -r requirements.txt