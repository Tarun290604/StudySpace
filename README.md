# Student Space

Student Space is a MERN (MongoDB, Express, React, Node.js) stack project designed to provide students with an integrated platform for managing their courses, accessing learning resources, and tracking their progress.

Check out the project [here](https://study-space-eight.vercel.app/).

## Key Features

- **User Authentication**: Secure user registration and login system.
- **Course Management**: Students can enroll in courses, view course details, and track their progress.
- **Instructor Dashboard**: Instructors can create, edit, and manage courses.
- **Responsive UI**: A user-friendly interface designed with React and Tailwind CSS.
- **Payment Integration**: Secure payment processing for course enrollments using Razorpay.
- **Data Visualization**: Instructors can view statistics and charts related to course engagement.

## Technologies Used

- **Backend**: Node.js, Express.js, MongoDB
- **Frontend**: React.js, Tailwind CSS
- **APIs**: Razorpay for payment processing
- **Cloud Services**: Cloudinary for image and video storage
- **Authentication**: JSON Web Tokens (JWT), bcrypt

## Screenshots

![Home Page](https://github.com/user-attachments/assets/56dbe5b6-a36b-4330-8706-685d60641d0c)
![Course Catalog](https://github.com/user-attachments/assets/93597c97-9835-4f37-9194-01e4c751e7f9)
![Course Details](https://github.com/user-attachments/assets/0e41256d-d273-45f5-b602-1ff73ec48a54)
![Instructor Dashboard](https://github.com/user-attachments/assets/27b0a481-1207-46b1-8db4-f6eeee947295)
![Student Dashboard](https://github.com/user-attachments/assets/13a16564-1334-4fd0-be7f-875ea4c05a5e)
![Payment Gateway](https://github.com/user-attachments/assets/d0777919-f22c-4947-8bc0-7fdc67f6da20)

## How to Run the Project

1. **Clone the repository**:
    ```bash
    git clone https://github.com/san1234sharma/Student-Space.git
    cd Student-Space
    ```

2. **Install the dependencies** for both frontend and backend:
    ```bash
    cd FrontEnd
    npm install
    cd ../server
    npm install
    ```

3. **Set up environment variables**:
    Create a `.env` file in the `server` directory and add the following variables:
    ```env
    PORT=4000
    MONGODB_URL=<your_mongodb_connection_string>
    JWT_SECRET=<your_jwt_secret>
    CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
    CLOUDINARY_API_KEY=<your_cloudinary_api_key>
    CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
    RAZORPAY_KEY_ID=<your_razorpay_key_id>
    RAZORPAY_KEY_SECRET=<your_razorpay_key_secret>
    ```

4. **Run the backend server**:
    ```bash
    cd server
    node index.js
    ```

5. **Run the frontend development server**:
    ```bash
    cd ../FrontEnd
    npm start
    ```

6. **Access the application**:
    Open your web browser and go to `http://localhost:3000` for the frontend and `http://localhost:4000` for the backend API.

## Acknowledgements

We developed Student Space as part of our learning journey in the YourStory Digital Hackathon, and we are grateful for the support and guidance from the Hackerearth and YourStory Digital Community.

---
