
📦 Jenkins Build Logs Backup to AWS S3

This project provides a simple Bash script to automatically upload Jenkins build logs generated today to an AWS S3 bucket. It helps in log backup, auditing, and troubleshooting.

🚀 Features
Scans all Jenkins jobs and their builds
Filters logs created on the current date
Uploads logs to AWS S3 with structured naming
Displays success and failure messages
Lightweight and easy to schedule (cron-friendly)
🛠️ Prerequisites

Make sure the following are installed and configured:

Jenkins (running locally)
AWS CLI
AWS credentials configured (aws configure)
Proper IAM permissions for S3 upload
📂 Script Overview

The script performs the following steps:

Checks if AWS CLI is installed
Iterates through Jenkins job directories
Finds build logs created today
Uploads them to the specified S3 bucket
