# Real-Time Chat System - MEAN Stack

## Overview
This project is a real-time text and video chat system developed using the **MEAN stack** (MongoDB, Express, Angular, Node.js) along with **Socket.io** for real-time messaging and **Peer.js** for video chat functionality. The system includes three levels of user roles: **Super Admin**, **Group Admin**, and **Chat User**, each with varying levels of permissions to manage groups and communicate with other users in real time.

## Technologies Used
- **MongoDB**: A NoSQL database used to store user data, group information, and chat history.
- **Express.js**: A fast, minimalist web framework for Node.js that handles the API and server-side logic.
- **Angular**: A powerful frontend framework used to build the user interface for the chat system.
- **Node.js**: The backend runtime environment for handling asynchronous server operations.
- **Socket.io**: A JavaScript library for enabling real-time communication between the server and clients.
- **Peer.js**: A WebRTC-based library used for enabling peer-to-peer video chat functionality.

## Installation

### Prerequisites
Ensure that you have the following installed on your system:
- **Node.js** (v14 or higher)
- **MongoDB** (latest stable version)
- **Angular CLI** (v12 or higher)

### Backend Setup
1. Clone this repository and navigate to the backend directory:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name/backend
