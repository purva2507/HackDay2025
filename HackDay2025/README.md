

# Flora AI - Smart farming solution for future cities

## Aim and Target

Motive:
The vision of a future city is one where AI seamlessly integrates into daily life, empowering residents to cultivate sustainable urban environments. Flora AI is inspired by the growing trend of home based urban gardening and terrace farming, crucial components of future city food systems. Imagine a city where every resident can easily diagnose plant diseases using their smartphones, contributing to a city wide network of plant health data. City planners can leverage this data to optimize urban farming policies, allocate resources effectively, and ensure the resilience of our green spaces. Flora AI bridges the gap between individual residents and city level sustainability, making urban agriculture faster, smarter, and more inclusive

Flora AI aims to address these challenges by providing a comprehensive, user-friendly platform. It offers people and horticulturists access to crop health details, organic and inorganic treatment options, expert chat support, and product comparisons, all in their preferred language.

Target Audience:

* Farmers and horticulturists.
* Members of the public interested in agriculture and planting.
* City planners and urban farmers involved in vertical and terrace farming.

## 1. Introduction

This repository contains the code for the Flora AI project. It's a web application that enables users to upload images of symptomatic plants and receive detailed plant information, including disease diagnoses. The application features a chat service for expert consultation and integrates the Google Translate API for multilingual support (113 languages). Built using the Flask framework, Flora AI prioritizes accessibility and sustainability.

Central to the application is its image recognition capability, which provides treatment recommendations based on uploaded images and user profiles. 

### 1.1. Features

* **Disease detection:** AI-powered image analysis for accurate diagnoses.
* **Disease management guide:** Organic and inorganic treatment recommendations.
* **Multilingual chat:** Real-time communication with subject experts.
* **Comparative product analysis:** Assists in selecting appropriate treatments.
* **Multilingual website:** Supports 113 languages.
* **User-friendly interface:** Designed for ease of use.

## 2. Installation

### 2.1. Requirements

* Python 3.6 or higher.
* Python packages:
    * `tensorflow==2.10.1`
    * `opencv-python==4.6.0`
    * `matplotlib==3.6.0`
    * `numpy==1.23.3`
    * `flask==2.2.2`
    * `geopy==2.3.0`
    * `wikipedia==1.4.0`
    * `exif==1.3.5`
    * `flask-socketio==5.3.2`

### 2.2. Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/purva2507/HackDay2025.git](https://www.google.com/search?q=https://github.com/purva2507/HackDay2025.git)
    cd HackDay2025](https://github.com/purva2507/HackDay2025.git)
    ```

2.  Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```


## 3. Running the project

1.  Navigate to the project directory:

    ```bash
    cd Flora-AI
    ```

2.  Run the application:

    ```bash
    python flora.py
    ```

3.  Access the application in your web browser: `http://127.0.0.1:4040/`

