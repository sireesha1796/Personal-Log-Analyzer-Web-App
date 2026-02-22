Personal Log Analyzer Web App
# Personal Log Analyzer Web App

## Overview
This is a simple web application to upload and analyze log files. It parses logs, identifies errors and warnings, and displays a summary dashboard. Optionally, it can suggest root causes using AI.

## Features
- Upload log files (.log/.txt)
- Parse and categorize logs: ERROR, WARN, INFO
- Count occurrences and list frequent errors
- Dashboard view for quick insights
- Optional AI-powered suggestions for root causes
- Store past logs in SQLite (optional)

## Tech Stack
- Python 3 + Flask
- HTML + Bootstrap
- SQLite (optional)
- Optional: Claude/OpenAI API for AI suggestions

## Setup Instructions
1. Clone the repository
```bash
git clone https://github.com/yourusername/personal-log-analyzer.git
