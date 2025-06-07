# Retail Price Optimization using MLOps

This project predicts the total retail price of a product using machine learning and MLOps principles. It integrates model training, experiment tracking, Docker containerization, CI/CD, and deployment.

## Features

- Regression model for price prediction
- MLflow for experiment tracking
- Flask API for real-time predictions
- Dockerized app for portability
- CI/CD pipeline via GitHub Actions
- Deployed on Render

## Tools & Technologies:
ML Libraries: Scikit-learn, Pandas, NumPy, Matplotlib

MLOps Stack: MLflow (experiment tracking), Docker (containerization), GitHub Actions (CI/CD pipeline), Render (cloud deployment)

Backend/API: Flask

Version Control & CI/CD: Git, GitHub

Containerization: Docker with environment reproducibility and dependency isolation

Deployment: Render Web Service with integrated deployment hooks


## Quick Start

```bash
git clone https://github.com/yourusername/retail-price-optimization-mlops.git
cd retail-price-optimization-mlops
pip install -r requirements.txt
cd app && python app.py

## CI/CD
GitHub Actions pipeline:

Link and test code

Build Docker image

Deploy to Render on push to main
