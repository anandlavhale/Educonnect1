![image](https://github.com/user-attachments/assets/790a3446-a6a0-4c51-bf57-e96eafdc99ac)
# Educonnect

https://educonnect-frontend-xoy8.onrender.com
 EduConnect is a full-stack web application that tracks teachers’ daily schedules and classroom locations, allowing students to view availability and book appointments. It is built using the MERN stack with a focus on real-time scheduling and teacher-student interaction.
# Education Web3 Backend

This is the backend for the Education Web3 application, built with Node.js, Express, and MongoDB.

## Setup

1. Install MongoDB on your system if you haven't already.
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file in the root directory with the following variables:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/education-web3
   JWT_SECRET=your_jwt_secret_key
   ```

## Running the Server

Development mode:
```
npm run dev
```

Production mode:
```
npm start
```

## API Endpoints

### Teachers
- `GET /api/teachers` - Get all teachers
- `GET /api/teachers/:id` - Get teacher by ID
- `POST /api/teachers` - Create a new teacher
- `PUT /api/teachers/:id/timetable` - Update teacher timetable
- `POST /api/teachers/auth` - Authenticate teacher

### Students
- `GET /api/students` - Get all students
- `GET /api/students/id/:id` - Get student by ID
- `GET /api/students/email/:email` - Get student by email
- `POST /api/students/register` - Register a new student
- `POST /api/students/login` - Login student

### Appointments
- `GET /api/appointments` - Get all appointments
- `GET /api/appointments/teacher/:teacherId` - Get appointments by teacher ID
- `GET /api/appointments/student/:studentId` - Get appointments by student ID
- `POST /api/appointments` - Create a new appointment
- `PUT /api/appointments/:id/status` - Update appointment status
- `DELETE /api/appointments/:id` - Delete appointment 

![image](https://github.com/user-attachments/assets/7c1e341c-5175-4270-b416-88f0a69d18eb)

![image](https://github.com/user-attachments/assets/02d4cdd7-3794-4ada-aa5d-1bd3f052493a)

![image](https://github.com/user-attachments/assets/1ce82298-bdfb-45cb-a16f-2c46b59ef2da)

![image](https://github.com/user-attachments/assets/4e6a5fda-db26-4a11-a4b0-e21d863b78da)


