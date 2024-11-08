# Restaurant Revenue Prediction API

Welcome to the Restaurant Revenue Prediction API! This API is designed to provide predictions for monthly revenue based on various restaurant metrics using machine learning. Built with Flask, this application serves both an interactive web interface and a RESTful API.

## Table of Contents

1. [Features](#features)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Running the Application](#running-the-application)
5. [API Endpoints](#api-endpoints)
6. [Testing the Application](#testing-the-application)
7. [Deployment with Docker](#deployment-with-docker)
8. [Configuration](#configuration)
9. [Troubleshooting](#troubleshooting)
10. [Future Improvements](#future-improvements)
11. [License](#license)

## Features

- Predict monthly revenue based on customer metrics and marketing strategies.
- Web interface for easy data input and interaction.
- API endpoints for programmatic access.
- Health check endpoint to verify model functionality.
- Logging of user messages for feedback and inquiries.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Python**: Version 3.7 or higher is required. You can download it from [python.org](https://www.python.org/downloads/).
- **Docker**: Optional for containerized deployment. You can get it from [docker.com](https://www.docker.com/get-started).

### Python Libraries

You will need the following Python libraries to run the application. They are specified in `requirements.txt`:

```plaintext
Flask
pandas
scikit-learn
numpy
matplotlib
seaborn
scipy
