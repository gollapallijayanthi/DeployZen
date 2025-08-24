**DeployZen** – Fast, Easy, Automated Deployment

DeployZen is a **cloud-based platform** that simplifies **static website deployment** for students and developers. It allows users to upload a ZIP file or connect a GitHub repository, and automatically handles hosting on **AWS S3** using **Lambda, DynamoDB, and a Flask backend**.

✨ With DeployZen, static site deployment becomes **fast, easy, and beginner-friendly**.

---

## 📖 Table of Contents

* [Abstract](#-abstract)
* [Problem Overview](#-problem-overview)
* [Objectives](#-objectives)
* [Architecture & Services](#-architecture--services)
* [Features](#-features)
* [Tech Stack](#-tech-stack)


---

##  Abstract

DeployZen automates the entire process of static site deployment:

* Upload a **ZIP file** or link a **GitHub repo**.
* Backend triggers **AWS Lambda** to unzip, host, and manage metadata in **DynamoDB**.
* **Flask (EC2)** handles routing, authentication, and URL redirection.
* Users can view deployed sites in a **public showcase (ZenHub)**.
* Authentication is secured with **AWS Cognito**.
* A **chatbot (Lex)** assists users with FAQs and deployment guidance.

---

##  Problem Overview

Students and beginners often struggle with deploying websites on cloud platforms like AWS due to:

* Complex S3 setup
* Permissions management
* Manual URL handling

DeployZen solves this by **removing the complexity** and offering a **one-click deployment experience**.

---

## Objectives

* Quick and seamless static website deployment
* Support for both **ZIP upload** and **GitHub repo deployment**
* Automated deployment using AWS Lambda
* Store metadata in DynamoDB
* Secure access with Cognito
* Public project showcase via **ZenHub**

---

## 🏗 Architecture & Services

* **Amazon Cognito** → User login & authentication
* **Amazon EC2** → Hosts Flask backend
* **Amazon S3** → Stores uploads & hosts static sites
* **AWS Lambda** → Automates unzipping & hosting
* **Amazon DynamoDB** → Stores deployment metadata
* **GitHub** → Direct repo deployment option
* **Amazon Lex** → Chatbot for user assistance

---

## ✨ Features

--  Upload ZIP or GitHub repo for deployment
--  Automatic static hosting with AWS S3
--  Unique short URLs with redirection
--  Project metadata tracking with DynamoDB
--  Public showcase page (**ZenHub**)
-- Secure login/signup with AWS Cognito
--  Interactive chatbot with AWS Lex

---

##  Tech Stack

* **Backend**: Flask (Python) on EC2
* **Frontend**: HTML + Tailwind CSS
* **AWS Services**: EC2, S3, Lambda, DynamoDB, Cognito, Lex
* **Other Tools**: UUID for short URLs



*DeployZen makes cloud deployment effortless, scalable, and beginner-friendly.*

