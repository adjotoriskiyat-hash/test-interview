# Bincom Tech Assessment - Polling Unit Results

This project is a technical assessment for the PHP/MySQL Developer Internship at Bincom Dev Center. As permitted in **Step 0 (Option C)** of the instructions, this solution is built using **JavaScript (Node.js/Express.js)** and **MySQL**.

## 🚀 Live Demo
[Insert Your Deployed Link Here]

## 🛠️ Technology Stack
* **Backend:** Node.js, Express.js
* **Frontend:** EJS (Embedded JavaScript templates), HTML/CSS
* **Database:** MySQL (Hosted on Aiven Cloud)

## 📋 Features Implemented

* **Question 1:** Displays the results for any individual polling unit from the `announced_pu_results` table.
* **Question 2:** Displays the summed total result of all polling units under a specific Local Government Area (LGA) using a dropdown selection and a `JOIN` query.
* **Question 3:** Provides a user-friendly form to store new election results for all political parties into the database.

## 💻 Local Setup Instructions

To run this project locally on your machine:

1. **Clone the repository:**
   ```bash
      git clone [https://github.com/adjotoriskiyat-hash/test-interview.git](https://github.com/adjotoriskiyat-hash/test-interview.git)
         cd test-interview

## Install dependencies:
         npm install
         
## Environment Variables:
      ```bash  
         Create a .env file in the root directory and add your database connection string:
         DATABASE_URL="your_mysql_database_url_here"
(Note: The database requires an SSL CA certificate to connect successfully).

## Start the server:
      node server.js

The application will be running on http://localhost:3000.

Developed by Adjoto-Sodiq Riskiyat Adejumoke