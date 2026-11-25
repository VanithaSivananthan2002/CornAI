🌽 CornAI – Corn Disease Classification System

📌 Project Overview

CornAI is a web-based corn leaf disease classification system developed using Machine Learning and Image Processing techniques. The system aims to help farmers identify common corn leaf diseases by uploading images of corn leaves.

The system uses a Convolutional Neural Network (CNN) model to analyze uploaded leaf images and predict the corresponding disease category. It provides a simple and user-friendly interface to support early disease identification and improve awareness of corn plant health.

🎯 Objectives

To develop an automated corn leaf disease classification system.

To identify diseases from uploaded corn leaf images.

To apply Machine Learning and Image Processing techniques.

To provide a user-friendly web application for farmers.

To support early identification of corn leaf diseases.

🌱 Supported Disease Categories

The system is designed to classify corn leaves into the following categories:

Common Rust – A fungal disease that produces reddish-brown or orange pustules on corn leaves.

Gray Leaf Spot – A disease that causes rectangular gray or tan lesions on corn leaves.

Healthy – Corn leaves without visible symptoms of the supported diseases.

🛠️ Technologies Used

Frontend

React.js

JavaScript

HTML5

CSS3

Tailwind CSS

Backend

Node.js

Express.js

MongoDB Atlas

Machine Learning API

Python

FastAPI

TensorFlow / Keras

OpenCV

NumPy

Pandas

Scikit-learn

Machine Learning

Convolutional Neural Network (CNN)

Image Processing

Image Classification

⚙️ Main Features

User registration and login

Upload corn leaf images

Automatic disease classification

Display prediction results

View prediction history

Dashboard for monitoring prediction activities

Delete prediction history by week, month, or all records

Update user profile

🏗️ System Architecture

CornAI consists of three main components:

Frontend: Provides the user interface for uploading images and viewing prediction results.

Backend: Handles user authentication, database operations, prediction requests, and communication between system components.

Machine Learning API: Processes uploaded images and uses the trained CNN model to predict corn leaf disease categories.📂 Project Structure

CornAI/
│
├── frontend/
│   ├── src/
│   └── package.json
│
├── backend/
│   ├── index.js
│   ├── routes/
│   ├── models/
│   └── package.json
│
├── ml_service/
│   ├── main.py
│   ├── Pro_Corn_Model.h5
│   └── requirements.txt
│
└── README.md

🔮 Future Improvements

Improve model prediction accuracy.

Expand the dataset with more corn leaf images.

Support additional corn diseases.

Improve prediction reliability under different lighting and environmental conditions.

Provide more detailed disease information and management recommendations.

👩‍💻 Project Information

Project Name: CornAI – Corn Disease Classification System

Project Area: Machine Learning, Image Processing and Web Development

Project Type: Undergraduate Project

University: Rajarata University of Sri Lanka

Faculty: Faculty of Technology

Department: Department of Information and Communication Technology

⭐ If you find this project interesting, feel free to explore the repository!
