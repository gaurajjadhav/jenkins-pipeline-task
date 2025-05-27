# Jenkins CI/CD Pipeline Task

This project demonstrates a **basic Jenkins CI/CD pipeline** to automate the build, test, and deployment stages of a simple Flask web application.


##  Tools Used
- Jenkins
- Docker (optional)
- Python + Flask


##  Project Overview
- A `Jenkinsfile` is used to define the pipeline stages:
  - **Build**: Simulate build process.
  - **Test**: Simulate testing process.
  - **Deploy**: Runs the Flask app.


##  App Info
The Flask app (`app.py`) runs on:


**URL:** `http://localhost:9090/`
Make sure port `9090` is free before running the app.


## **Expected Output**
'Hello I'm Gauraj from Jenkins CI/CD with Docker!'


## 🖥 Run Locally
If running manually:

```bash
pip install flask
python app.py

