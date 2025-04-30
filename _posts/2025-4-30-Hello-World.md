---
layout: post
title: Gym Companion App
---

##  Project Overview
The **Gym Companion App** is a mobile application designed to help users log and monitor their gym progress while providing AI generated workoutx and meal plans tailored to their fitness goals. This project aims to bridge the gap between technology and personal well-being, by integrating AI and fitness tracking into a single, user friendly platform.

Here is the URL for the Web version: [https://gym-companion.expo.app/](https://gym-companion.expo.app/)

> **Note:** This is primarily a mobile app. However, a web version was also created using the Expo React Native framework. If using the web version, you must disable any pop-up blocker you may have as this prevents Auth0 from working. This is primarily an issue on **Safari** but may occur in other browsers too.

## Features
- **AI Generated Plans**: Personalised workout and meal plans based on user inputs.
- **Progress Tracking**: Log workouts and track improvements over time.
- **Nutrition Guidance**: Custom meal plans.
- **User Friendly Interface**: Simple and intuitive UI for all fitness levels.

## Technologies Used
### **Frontend**
- **React Native (with Expo)** – Cross platform mobile development, supporting both iOS, Android and also Web.

### **Backend**
- **Node.js, Typescript and Express.js** – REST API server with token-based authentication.
- **PostgreSQL** - Relational database for structured data.

### **AI Integration**
- **OpenAI API** - Generates personalised workout and meal plans.
- **jsonrepair** – Used to clean and validate AI responses before saving to the database.


### **Development & Deployment**
- **GitHub Actions** – Automated CI/CD pipeline for build and deployment.
- **Docker & Docker Compose** – Containerisation for local and cloud deployment.
- **Kubernetes (Azure AKS)** – Used for cloud hosting.
- **Agile SCRUM Methodology** - Managed with Trello.

## **User Interface**
<p align="center">
  <img src="{{ site.baseurl }}/images/homepage.png" alt="Gym Companion Home Page">
</p>

## System Design
![_config.yml]({{ site.baseurl }}/images/fyp.png)

## ERD of Tables
<p align="center">
  <img src="{{ site.baseurl }}/images/db.png" alt="Database schema">
</p>