## ConnectSphere

## Project Overview

The project is about a social web application, named ConnectSphere. It is a modern, stateful web application designed to facilitate social interactions and community engagement. This platform enables users to connect, communicate, and share content through a robust set of features. The application supports user authentication, role management, social networking functionalities, and multimedia sharing, all while maintaining a seamless user experience.

## Tech Stacks

```markdown
### Tech Stack

#### Backend
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-Framework%20for%20Java-red)  
![MySQL](https://img.shields.io/badge/MySQL-Relational%20Database%20Management%20System-orange)  
![Java 11](https://img.shields.io/badge/Java%2011-Version%2011-blue)

#### Frontend
![React](https://img.shields.io/badge/React-Library-green)  
![npm](https://img.shields.io/badge/npm-Package%20Manager-red)

#### Deployment
![Heroku](https://img.shields.io/badge/Heroku-Deployment%20Platform-purple)  
```

## Key Features

- **User Authentication**

  
  - Register, Login, and Logout functionality.
  - User roles: Root, Admin, and User.
  - Role Management: Promote/Demote users between Admin and User roles.
  - User Management: Create and delete users; Edit user profiles.
 
- **Social Networking**

  
  - Search for friends.
  - Send and accept friend requests.
  - Remove friends from the friends list.
 
- **Content Management**

  
  - Add and delete photos.
  - Create and delete posts.
  - Create and delete comments.
 
- **Chat Functionality**
  - Real-time messaging with friends.
 
  
- **Logs History:**
- Track application activities and user interactions.

## Development and Deployment

### Local Development

1. **Starting the Client:**

   - Navigate to the client directory:
     ```bash
     $ cd SocialNetwork/Client
     ```
   - Install dependencies:
     ```bash
     $ npm install
     ```
   - Run the application in development mode:
     ```bash
     $ npm start
     ```
   - Access the client application at [http://localhost:3000](http://localhost:3000).

2. **Starting the Server:**

   - Navigate to the server directory:
     ```bash
     $ cd SocialNetwork/Server
     ```
   - Start the server:
     ```bash
     $ mvn spring-boot:run
     ```
   - The server will be running on port 8000.

### Docker Deployment

1. **Starting the Application:**

   - Navigate to the project root directory:
     ```bash
     $ cd SocialNetwork/
     ```
   - Launch the application using Docker Compose:
     ```bash
     $ docker-compose up -d
     ```
   - Access the front-end application at [http://localhost:9090](http://localhost:9090).

2. **Stopping the Application:**

   - To stop the running containers:
     ```bash
     $ docker-compose down
     ```

### Configuration

To enable photo storage, sign up for a Cloudinary account and configure the credentials in the `application.properties` file located at `SocialNetwork/Server/src/main/resources/application.properties`.

**Admin Credentials:**
- **Username:** john
- **Password:** 1111

## Notes

- Ensure Java 11 is installed for running the backend server.
- Follow the setup instructions for both manual and Docker-based development to configure your environment effectively.

For further information, please refer to the documentation provided in the respective directories or contact the project maintainers.

## App screenshots

1. **Home Page**

 ![j](https://github.com/user-attachments/assets/521396e1-0087-4d9b-9269-96e12cc065a1)


2. **Friends Page**

![H](https://github.com/user-attachments/assets/ebc18212-b0fc-49b3-9c6f-a542811db447)

3. **Photos Page**

![I](https://github.com/user-attachments/assets/90f01ecf-1210-42dd-ad99-9c88c97da79c)

 ## My Contrubutions

In this Social Media application, I played a crucial role by applying my skills in Java and JavaScript. I focused on developing the back-end using Spring Boot, handling core functionalities such as user authentication, role management, and chat features, all integrated with MySQL for effective data management. For the front-end, I used React to build a user-friendly interface where users can manage friends, photos, and posts. My team members took care of integrating Cloudinary for photo storage and Docker for containerization, ensuring the app ran smoothly and was easy to deploy.
