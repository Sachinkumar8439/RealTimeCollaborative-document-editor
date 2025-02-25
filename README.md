# RealTimeCollaborative-document-editor

**COMPANY**: CODITECH IT SOLUTIONS

**NAME**: SACHIN KUMAR

**INTERN ID**: CT6WGWQ

**DOMAIN**: FULL STACK WEB DEVELOPMENT

**BATCH DURATION**: January 10th, 2025 to February 25th, 2025.

**MENTOR NAME**: NEELA SANTHOSH KUMAR

# OUTPUTS

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">

<img src="https://github.com/user-attachments/assets/08592081-0f41-48ee-9677-813509b432ff" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/d4459f39-fd35-46ab-a1d1-8dccf413db74" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/e10ee4f5-a458-439e-89ae-6f48881701c7" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/fc671f61-08d0-46c3-bcd4-48a8e9d7a343" alt="Image" width="400">

<img src="https://github.com/user-attachments/assets/6b8a1f4d-13e8-4ecd-9f68-deea888dd974" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/ee91e984-ef28-49a4-960b-07bdc3a5e83e" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/cc409350-e472-4971-b88f-a5ae7e3df9ba" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/67c07eb6-726c-4783-8602-6d0f05e18d70" alt="Image" width="400">

<img src="https://github.com/user-attachments/assets/e56dff2f-e732-442e-a7fb-f5c95da8e826" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/d5cc7b71-5284-401d-8e78-b948a33b1d0c" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/f523ce78-98e1-4d51-9e8f-617e1ebc9caf" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/90743db8-69de-400e-939f-8ca671d91c1c" alt="Image" width="400">

<img src="https://github.com/user-attachments/assets/20f94e60-6539-45cd-b9e2-fccdbaa9be63" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/0553106f-c1e1-4195-9b09-cb63d0f0c2b5" alt="Image" width="400">
<img src="https://github.com/user-attachments/assets/5f7a374b-1250-47bf-b6e4-e61b63f105fc" alt="Image" width="400">

</div>

## Project Overview

The **Real-Time Collaborative Document Editor** is a web application that allows users to create and edit documents. The project is currently in development, with the following features implemented so far:
- **User Authentication**: Users can log in or sign up securely.
- **Document Creation and Saving**: Users can create documents and save them to a MongoDB database.
- **Editing Capabilities**: Documents can be written and edited by the user who created them.

The next phase of development involves enabling real-time collaborative editing for multiple users using **Socket.io**.

---

## Features

### Completed Features:
1. **User Authentication**
   - Secure login and sign-up functionality.
   - Passwords are securely stored.

2. **Document Management**
   - Users can create and save documents.
   - Documents are stored in **MongoDB**.

3. **Basic Editing**
   - A user can write and edit their own documents.

### Upcoming Features:
1. **Real-Time Collaboration**
   - Multiple users will be able to edit the same document simultaneously in real time.
   - Changes will be synchronized across all connected clients.

2. **User Roles and Permissions**
   - Implement roles for viewers and editors for better document control.

3. **Rich Text Editor**
   - Add support for text formatting options such as bold, italic, lists, and more.

---

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.io
- **Other Libraries and Tools**:
  - **CORS**: To handle cross-origin requests.
  - **Body-Parser**: For handling HTTP POST request payloads.

---

## Installation and Setup
---

### **Prerequisites**
Ensure you have the following installed on your system:
1. **Node.js** (v14 or above) - [Download Node.js](https://nodejs.org/)
2. **MongoDB** - [Install MongoDB](https://www.mongodb.com/try/download/community)
3. **Git** - [Install Git](https://git-scm.com/)

---

### **Step 1: Clone the Repository**
1. Open your terminal/command prompt.
2. Run the following command to clone the repository:
   ```bash
   git clone https://github.com/Sachinkumar8439/RealTimeCollaborative-document-editor.git
   ```
3. Navigate to the project directory:
   ```bash
   cd RealTimeCollaborative-document-editor
   ```

---

### **Step 2: Install Dependencies**

#### For the Server:

1. Install the required dependencies:
   ```bash
   npm install
   ```

#### For the Client:
2. Install the required dependencies:
   ```bash
   npm install
   ```

---

### **Step 3: Configure Environment Variables**
1. Create a `.env` file in the `server` directory.
2. Add the following environment variables:
   ```env
   MONGO_URI=your-mongodb-uri
   ```
   Replace `your-mongodb-uri` with your MongoDB connection string.

---

### **Step 4: Start MongoDB**
1. Ensure MongoDB is running locally.  
   On Linux/Mac:
   ```bash
   mongod
   ```
   On Windows, start the MongoDB service from the Services Manager.

---

### **Step 5: Run the Application**

#### Start the Server:
2. Start the server:
   ```bash
   node server.js
   ```

#### Start the Client:
1. Start the client:
   ```bash
   npm start
   ```

---

### **Step 6: Access the Application**
1. Open your browser.
2. Navigate to:
   ```plaintext
   http://localhost:3000
   ```

---




   



