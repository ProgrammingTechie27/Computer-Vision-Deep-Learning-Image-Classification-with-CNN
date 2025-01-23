# Image Classification Model Deployment with Flask and TensorFlow Serving

This project demonstrates the process of deploying a pre-trained image classification model using Flask for web-based interaction and TensorFlow Serving for scalable, high-performance model serving.

## Table of Contents
1. [Overview](#overview)
2. [Setup Instructions](#setup-instructions)
3. [How to Test the Model](#how-to-test-the-model)
4. [Flask API](#flask-api)
5. [TensorFlow Serving](#tensorflow-serving)
6. [Requirements](#requirements)
7. [License](#license)

## Overview

This project uses a pre-trained image classification model that is served via TensorFlow Serving. The model is saved in the TensorFlow `SavedModel` format and is integrated with a Flask app that allows users to upload images and receive predictions with probabilities for each prediction.

### Key Features:
- Image classification using a TensorFlow model.
- Flask-based web application to accept user inputs (image files).
- Predictions and class probabilities returned in response.
- Model deployed using TensorFlow Serving for efficient inference.

## Setup Instructions

### Step 1: Install Required Dependencies

In the requirements.txt you will find all the dependencies needed in order to replicate the environment to run the code.
