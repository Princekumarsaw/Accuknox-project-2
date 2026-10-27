# AccuKnox DevOps Trainee Assessment — Problem Statement 2

## Overview

This project contains two Bash scripts developed for the AccuKnox DevOps Trainee practical assessment.

## 1. System Health Monitoring Script

`File:scripts/system_health.sh`

Features:
- Monitors CPU usage.
- Checks memory utilization.
- Checks root disk usage.
- Counts running processes.
- Generates alerts when configurable thresholds are exceeded.
- Saves output to a log file.

`Run:./scripts/system_health.sh`

## 2. Application Health Checker

`File:scripts/app_health_check.sh`

Features:
- Accepts an application URL as input.
- Checks HTTP response status codes.
- Uses connection and request timeouts.
- Reports the application as UP or DOWN.
- Returns an appropriate exit code.

`Run:./scripts/app_health_check.sh https://example.com`

## Technologies Used

- Bash scripting
- Linux commands
- curl
- Git and GitHub

## Testing

Both scripts were syntax-checked and tested with sample commands. Actual results depend on system resources and application availability.
- Bash scripting
- Linux commands
- curl
- Git and GitHub

## Testing

Both scripts were syntax-checked and tested with sample commands. Actual results depend on system resources and application availability.
