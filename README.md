# Social Media Platform

## Project Overview
This project is a comprehensive social media platform that includes features such as user accounts with authentication and friend management, real-time chat using sockets, notifications, post uploads, and search functionality. The client is built with Vue.js using Pinia for state management and Tailwind CSS for design. The backend is developed with Django and PostgreSQL, served with Gunicorn, and containerized using Docker for seamless development and deployment.

## Key Features
- **User Accounts**: Authentication, authorization, and friend management.
- **Real-Time Chat**: Instant messaging using sockets.
- **Notifications**: Real-time notifications for various user activities.
- **Post Uploads**: Users can upload and share posts.
- **Search Functionality**: Search for users, posts, and other content.

## Technologies Used
- **Frontend**: Vue.js, Pinia, Tailwind CSS
- **Backend**: Django, PostgreSQL
- **Real-Time Communication**: Sockets
- **Server**: Gunicorn
- **Containerization**: Docker

## Running with Docker Compose

### Prerequisites
- Docker and Docker Compose installed

### Steps
1. **Clone the Repository**
    ```bash
    git clone https://github.com/almoghindi/Django-Vue-Social-Media.git
    cd Django-Vue-Social-Media
    ```

2. **Create Environment Variables**
    Create a `.env` file in the root directory with the necessary environment variables for Django and PostgreSQL.

3. **Build and Run the Containers**
    ```bash
    docker-compose up --build
    ```

4. **Access the Application**
    - **Frontend**: Open your browser and navigate to `http://localhost:8080`
    - **Backend**: The API will be available at `http://localhost:8000`

By following these steps, you can run the social media platform locally using Docker Compose, which sets up the frontend, backend, and database services.
