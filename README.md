---

# Job Seeker Platform

This is a full-stack web application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. It serves as a platform for job seekers to find and apply for job opportunities posted by employers.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely. Passwords are hashed and stored securely in the database.
  
- **Job Listings**: Employers can post job listings with details such as job title, description, requirements, and location.

- **Job Search**: Job seekers can search for job listings based on keywords, location, and other filters.

- **Apply for Jobs**: Job seekers can apply for job listings directly through the platform. Employers can review applications and contact applicants.

- **User Profiles**: Users have profiles where they can manage their job applications, update their information, and view their application history.

- **Responsive Design**: The application is built with responsive design principles, ensuring a seamless experience across devices.

## Technologies Used

- **Frontend**: React.js, React Router, Redux for state management, Bootstrap for styling
  
- **Backend**: Node.js, Express.js
  
- **Database**: MongoDB with Mongoose ORM
  
- **Authentication**: JSON Web Tokens (JWT)
  
- **Deployment**: The application is deployed on [Render](#) and uses MongoDB Atlas for database hosting.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository: `git clone <repository-url>`
  
2. Navigate to the project directory: `cd job-seeker-platform`
  
3. Install dependencies: `npm install`
  
4. Create a `.env` file in the root directory and add the necessary environment variables:

    ```
    PORT=5000
    MONGODB_URI=<your-mongodb-uri>
    JWT_SECRET=<your-jwt-secret>
    ```

5. Run the development server: `npm start`

6. Navigate to `http://localhost:3000` in your web browser to view the application.

## Deployment

This project is deployed on Heroku. You can access the live version of the application [here](#).
