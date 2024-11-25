# System Resource Monitor with Email Alerts

A Python script that monitors system resources (CPU, RAM, and Disk usage) and sends email alerts via Mailjet when usage exceeds defined thresholds.

## Features
- Real-time monitoring of CPU, RAM, and Disk usage
- Automated email alerts for threshold violations
- Configurable threshold values
- Secure credential management using environment variables

## Prerequisites
- Python 3 installed.
- Mailjet account with an API key and secret key.
- Virtual environment set up for Python development.

## How to Run the Script
### 1. Sign Up for Mailjet
- Create a free account at [Mailjet](https://www.mailjet.com/).
- Access the **Developer Portal** to generate your API Key and Secret Key.

### 2. Set Up the Python Environment
- Create a virtual environment:
  ```bash
  python3 -m venv <environment_name>

### 3. Activate the virtual environment

### 4. Clone the repository:
- ```bash
git clone https://github.com/MichaelOppong731/System_monitoring.git
cd System_monitoring

### 5. Install required packages:
-```bash
pip install mailjet_rest psutil

### 6. Set environment variables:
- ```bash
export MAILJET_API_KEY='your_api_key'
export MAILJET_API_SECRET='your_api_secret'

### 7. Run the script:
- ```bash
python monitor.py
