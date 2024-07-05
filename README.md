# 100 ACRES | Real Estate App with Real-Time Chat Functionality

![Screenshot 2024-07-05 at 2 24 08 PM](https://github.com/themihirmathur/100-acres/assets/92594107/660a5d59-46f8-48c7-8d5e-fa7277478435)

## Introduction

Welcome to the Real Estate App, a full-stack application built using the MERN stack (MongoDB, Express.js, React, Node.js) with additional technologies and tools such as Prisma, JWT, Cookies, Context API, and React Router Dom. This application provides users with a seamless experience for browsing real estate listings, managing their profiles, and engaging in real-time chat with other users.

## Features

- **User Authentication**: Secure user registration and login with JWT and Cookies.
- **Real-Time Chat**: Engage in real-time conversations using Socket.io.
- **CRUD Operations**: Full CRUD functionality for managing real estate listings.
- **Profile Management**: View and manage user profiles, including profile posts.
- **Image Upload**: Upload and manage images for property listings.
- **Rich Text Editor**: Create and edit property descriptions with a rich text editor.
- **Protected Routes**: Secure access to protected routes using JWT and React Router Dom.
- **Data Fetching**: Fetch data efficiently based on URL queries and display loading skeletons.
- **State Management**: Manage application state with Context API and Zustand.
- **Responsive Design**: Optimized for various screen sizes and devices.

![Screenshot 2024-07-05 at 2 24 26 PM](https://github.com/themihirmathur/100-acres/assets/92594107/0b163251-d36c-42ac-8bb8-5b16b201d62a)

## Technologies Used

### Frontend

- **React**: A JavaScript library for building user interfaces, providing a component-based architecture.
- **React Router Dom**: A routing library for React that allows navigation between different views and enables the use of dynamic routing in the application.
- **Context API**: A React API used to manage and share state across the entire application, making it easier to handle global state.
- **Zustand**: A lightweight state management library for React, offering an alternative to Context API for more complex state management needs.
- **Socket.io**: A library that enables real-time, bidirectional, and event-based communication between the client and server, used for implementing the chat functionality.
- **Rich Text Editor**: A component that allows users to create and format text content with rich formatting options, enhancing user experience when adding property descriptions.
- **Image Upload**: Provides functionality to upload and display images for property listings, enhancing the visual representation of properties.

![Screenshot 2024-07-05 at 2 24 50 PM](https://github.com/themihirmathur/100-acres/assets/92594107/f1e636f8-de8c-4127-8a17-c2476aa9aded)

### Backend

- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine, used for building the backend server.
- **Express.js**: A fast, unopinionated, minimalist web framework for Node.js, used to build the RESTful API and handle routing, middleware, and HTTP requests.
- **Prisma**: An ORM (Object-Relational Mapping) tool used to interact with the MongoDB database, providing type-safe database access and simplifying database operations.
- **JWT (JSON Web Token)**: A compact, URL-safe means of representing claims to be transferred between two parties, used for secure user authentication.
- **Cookies**: Small pieces of data stored on the client-side, used in conjunction with JWT for maintaining user sessions and authentication status.
- **Socket.io**: Also used on the backend to handle real-time communication and manage WebSocket connections for the chat functionality.

### Database

- **MongoDB**: A NoSQL database known for its flexibility and scalability, used to store application data such as user information, property listings, and chat messages.

![Screenshot 2024-07-05 at 2 23 27 PM](https://github.com/themihirmathur/100-acres/assets/92594107/2b086d8b-7964-4d97-a5a4-510661933f6f)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/real-estate-app.git
   cd real-estate-app
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. Set up environment variables in a `.env` file for the backend:
   ```plaintext
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

4. Start the development server:
   ```bash
   cd client
   npm start
   cd ../server
   npm start
   ```

## App Structure

- **Client**: Contains the React frontend code.
- **Server**: Contains the Node.js backend code.
- **Prisma**: Manages the database schema and migrations.

## Detailed Feature Descriptions

### User Authentication

Secure user authentication is implemented using JWT and Cookies. JWT is used to generate tokens that verify the identity of users. Cookies are used to store these tokens securely on the client-side, ensuring that user sessions are maintained even after the browser is closed.

### Real-Time Chat

The real-time chat functionality is powered by Socket.io, which allows users to engage in instant messaging. Socket.io enables real-time, bidirectional communication between the client and server, ensuring that messages are delivered instantly.

### CRUD Operations

The application supports full CRUD (Create, Read, Update, Delete) operations for managing real estate listings. Users can add new properties, view existing listings, update property details, and delete listings as needed.

### Profile Management

Users can view and manage their profiles, including viewing their posts and updating personal information. This feature ensures that users have control over their personal data and activity within the app.

### Image Upload

The image upload functionality allows users to upload images for their property listings. This enhances the visual appeal of the listings and provides potential buyers with a better understanding of the properties.

### Rich Text Editor

The rich text editor component enables users to create and format property descriptions with various text formatting options. This ensures that property listings are detailed and professionally presented.

### Protected Routes

Protected routes are implemented using JWT and React Router Dom to ensure that only authenticated users can access certain parts of the application. This enhances security and prevents unauthorized access.

### Data Fetching

Efficient data fetching techniques are used to load data based on URL queries and display loading skeletons while data is being fetched. This improves user experience by providing visual feedback during data retrieval.

### State Management

State management is handled using Context API and Zustand. Context API is used for global state management, while Zustand provides a more scalable solution for complex state management needs.

### Responsive Design

The application is designed to be responsive, ensuring that it works well on various devices and screen sizes. This ensures a consistent user experience across different platforms.

---

For detailed code and more information, contact [Mihir Mathur](https://mail.google.com/mail/u/0/?fs=1&tf=cm&source=mailto&to=themihirmathur@gmail.com).

![Screenshot 2024-07-05 at 2 24 35 PM](https://github.com/themihirmathur/100-acres/assets/92594107/952709c5-6796-4f74-95e7-fc6f0501a247)
