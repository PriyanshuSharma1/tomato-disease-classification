# Tomato Disease Classification using CNN

This project aims to develop a Convolutional Neural Network (CNN) model to classify tomato diseases. The project involves model building, backend server setup, model optimization, and deployment.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Model Optimization](#model-optimization)
- [API Server](#api-server)
- [Frontend](#frontend)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Overview

Tomato disease classification is an essential task for ensuring healthy crop production. This project uses a CNN model to accurately classify various tomato diseases from images. The model is built and trained using TensorFlow and deployed using FastAPI for backend services, with a React.js and React Native frontend.

## Features

- **Model Building**: Uses TensorFlow to build a CNN for disease classification.
- **Data Augmentation**: Enhances the training dataset for better model generalization.
- **Backend Server**: Uses FastAPI to serve the model and handle API requests.
- **Model Optimization**: Utilizes TensorFlow Lite for model quantization and optimization.
- **Frontend**: Includes a React.js web interface and a React Native mobile app.
- **Deployment**: Deploys the backend and model on Google Cloud Platform (GCP).

## Technologies

- **Model Building**: TensorFlow, CNN, Data Augmentation
- **Backend Server**: FastAPI, TensorFlow Serving
- **Model Optimization**: TensorFlow Lite
- **Frontend**: React.js, React Native
- **Deployment**: Google Cloud Platform (GCP)

## Installation

### Prerequisites

- Python 3.8 or higher
- Node.js and npm
- Docker (for TensorFlow Serving)
- Google Cloud SDK

### Clone the Repository

```bash
git clone https://github.com/your-username/tomato-disease-classification.git
cd tomato-disease-classification
