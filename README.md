# Repo-Xeni8
For Private Repositories 
### Hi, I'm Raphael 👋

I'm an Information Technology and Data Analytics student focused on building full-stack web applications, turning raw data into interactive machine learning tools, and maintaining reliable network infrastructure.

---

### Featured Projects

#### TorontoRiders.ca — Car Rental Platform *(Private Team Repository)*
A full-stack car rental web application featuring a multi-page responsive frontend, role-based portals for customers and fleet businesses, and a RESTful API backend.

* **My Role:** Full-Stack Developer / Collaborator
* **Tech Stack:** Node.js, Express, MongoDB, JavaScript, HTML5, CSS3, JWT, REST APIs
* **Key Contributions & Architecture:**
  * **RESTful API & Database Design:** Built modular Express routes and MongoDB schemas (`User`, `Vehicle`, `Booking`) supporting vehicle filtering, booking creation, and automated availability/conflict checking.
  * **Authentication & Role-Based Access:** Implemented secure JWT-based sign-up/sign-in flows and middleware separating **Customer** permissions (vehicle search, booking/checkout with add-ons, rental management) from **Business** capabilities (fleet CRUD operations, booking status updates, admin analytics dashboard).
  * **Resilient Frontend Integration:** Connected multi-page views to the backend via a centralized `api-client.js` layer with an offline `localStorage` fallback mode for serverless testing.
* *Note: Repository is kept private for team and project integrity. Live demo and code walkthrough available upon request.*

---

#### Employee Attrition Predictor *(Private Repository)*
A browser-based machine learning web application that predicts employee turnover risk in real time without requiring a backend server. Trained on the **IBM HR Analytics dataset** (1,470 employee records across 35 features), the tool evaluates employee inputs—such as age, income, job role, tenure, satisfaction, and overtime—to generate instant risk assessments.

* **My Role:** Data Analyst & Front-End Developer
* **Tech Stack:** Python, JavaScript, HTML5, CSS3, Bootstrap 5.3
* **Key Contributions & Architecture:**
  * **Multi-Model Ensemble:** Implemented three classification models—**KNN (K=9, 86% accuracy)**, **Naive Bayes (79% accuracy)**, and **Decision Tree (76% accuracy)**—to output individual "Will Leave / Will Stay" classifications, confidence scores, and an averaged overall risk tier (Low, Medium, or High).
  * **Zero-Server Client Execution:** Built both a lightweight rule-based JavaScript scoring engine (~90% parity) and a Python-to-JSON pre-computation pipeline (`generate_predictions.py`) that extracts trained model patterns into static JSON for instant browser inference (~95% parity).
  * **Explainable UI:** Designed a responsive Bootstrap interface with transparent feature-importance breakdowns showing which variables drive each prediction.
* *Note: Repository is kept private for team and academic integrity. Live demo and code walkthrough available upon request.*

---

### Technical Skills

* **Full-Stack & Web Development:** JavaScript, Node.js, Express, MongoDB, RESTful APIs, JWT Authentication, HTML5, CSS3, Bootstrap 5, Git/GitHub
* **Data & Machine Learning:** Python, Supervised Classification (KNN, Naive Bayes, Decision Trees), Exploratory Data Analysis, Feature Importance, JSON Model Serialization
* **Systems & Networking:** SDLC, Requirements Engineering, System Analysis & Design, TCP/IP, LAN/WAN Technologies, Windows Server Maintenance, Hardware Diagnostics
