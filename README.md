# Interactive Market Dashboard for Used Vehicle Listings
Interactive web dashboard for exploring used vehicle market data, built with Python and Streamlit, and deployed to the cloud for real-time access.

## Project Overview
This project delivers an interactive web dashboard designed to explore and visualise used vehicle market data. The application allows users to dynamically analyse key attributes such as mileage and pricing using interactive charts.

The focus of the project is not advanced modelling, but **end-to-end delivery**: from exploratory data analysis to building, deploying, and maintaining a live web application in the cloud.

---

## Business Context
Interactive dashboards are commonly used by analytics, marketing, and operations teams to explore datasets quickly and support decision-making without requiring technical expertise.

This project demonstrates the ability to:
- Prepare data for visual exploration
- Build user-facing analytical tools
- Deploy a production-ready application to a cloud platform

---

## Application Features
The web application includes:
- A clear application header
- Interactive controls (buttons or checkboxes)
- A histogram to explore vehicle attributes
- A scatter plot to analyse relationships between variables
- Responsive layout for browser-based usage

---

## Dataset
The application uses a CSV dataset of used vehicle listings, containing attributes such as:
- Mileage (odometer)
- Price
- Vehicle characteristics

The dataset is loaded dynamically into the application and used to generate interactive visualisations.

---

## Exploratory Data Analysis (EDA)
Before building the dashboard, an exploratory analysis was conducted in a Jupyter Notebook to:
- Understand the structure and quality of the dataset
- Test visualisation ideas using Plotly Express
- Validate which variables were most suitable for interactive exploration

The notebook is included in the repository for transparency and reproducibility.

---

## Technology Stack
- Python  
- pandas  
- Plotly Express  
- Streamlit  
- GitHub  
- Render (cloud deployment)

---

## Deployment
The application is deployed as a cloud-based web service using **Render**, enabling access through a public URL.

Deployment includes:
- Dependency management via `requirements.txt`
- Automated build and start commands
- Manual redeployment from GitHub when updates are made

---

## Repository Structure
used-vehicle-market-dashboard/
├── app.py # Streamlit web application
├── vehicles_us.csv # Dataset
├── requirements.txt # Project dependencies
├── README.md
└── notebooks/
└── EDA.ipynb # Exploratory data analysis


---

## Outcome
This project demonstrates the ability to move beyond analysis and deliver a **fully deployed, interactive analytics product**. It highlights skills in data exploration, application development, and cloud deployment — all critical for modern data and analytics roles.

---

## Author
**Erika González**  
MBA | Marketing & Data Analytics  
Focus areas: Data Products, Analytics Engineering, Business Intelligence
