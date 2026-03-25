# GearShare 

**GearShare** is a web application platform designed to foster community sharing. It enables neighbors within the same apartment complex or local neighborhood to freely and securely exchange tools, gear, and equipment. 

*This project was developed as a collaborative student project at Metropolia UAS.*

## Tech Stack

**Backend & Database:**
* **Runtime:** Node.js
* **Framework:** Express.js (REST API Endpoints)
* **Database:** MongoDB (Atlas)
* **ODM:** Mongoose
* **Authentication:** JSON Web Tokens (JWT)
* **File Handling:** Multer (for equipment image uploads)

## My Role & Contributions

In this project my specific contributions included:

* **RESTful API Development:** Designed and implemented robust API endpoints using Node.js and Express.js to handle client-server communication.
* **Security & Authentication:** Implemented secure user registration and login flows using JWT (JSON Web Tokens) to protect user data and restrict route access.
* **Media Handling:** Configured `Multer` middleware to process and store image uploads for user gear listings.

## Core Features

* **User Authentication:** Secure sign-up and login logic.
* **Tool Inventory:** Users can create, read, update, and delete (CRUD) their own gear listings.
* **Image Uploads:** Users can upload photos of the equipment they are sharing.
