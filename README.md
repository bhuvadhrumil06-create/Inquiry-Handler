# Inquiry Handler 🎓

**Inquiry Handler** is a comprehensive college admission inquiry management system designed to streamline the admissions process. By connecting colleges, faculty, and counselors onto a single platform, it ensures a seamless experience for prospective students and efficient workflow for educational institutions.

## 🌟 Key Features

The platform provides role-based features tailored for different stakeholders:

### 🏛️ For Colleges / Administrators
- **Manage Faculty and Counselors:** Easily add, remove, and oversee your team with role-based access and performance tracking.
- **Dashboard Overview:** Centralized view of all inquiries, track progress, and monitor counselor performance with real-time updates.
- **Master Data Management:** Manage branches, courses, and roles efficiently.

### 👨‍🏫 For Faculty
- **Inquiry Form Submission:** Submit structured inquiry forms with detailed student information and required documentation.
- **Allocate Inquiries:** Assign inquiries to the right counselors based on workload, expertise, and student preferences.

### 👥 For Counselors
- **Verify Student Information:** Ensure the accuracy of student data by cross-checking submitted details and validating credentials.
- **Status Management:** Seamlessly update inquiry statuses (e.g., Pending, Verified, Resolved, Closed), track progress, and provide timely updates to students.

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS (Embedded JavaScript templates), HTML5, CSS3, Bootstrap
- **Database:** MongoDB, Mongoose ODM
- **Authentication & Sessions:** express-session

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [MongoDB](https://www.mongodb.com/) installed and running locally, or a MongoDB Atlas URI

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Inquiry-Handler-Diya
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment Variables:**
   Create a `.env` file in the root directory and add any necessary environment variables.
   ```env
   PORT=3000
   ```

4. **Start the application:**
   For development with auto-restart:
   ```bash
   npm start
   ```

5. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`

## 📂 Project Structure

- `controllers/`: Business logic for handling requests (Admin, Counselor, Faculty, Master).
- `models/`: Mongoose schemas defining the database structure (Admin, Branch, Counselor, Course, Faculty, Inquiry, etc.).
- `routers/`: Express routes for different modules.
- `views/`: EJS templates for rendering the frontend interfaces (Admin, Counselor, Faculty, Master panels, and Landing pages).
- `public/`: Static assets such as images, CSS, and client-side JavaScript.
- `server.js`: The entry point of the application setting up the Express server and middleware.

## 📄 License

This project is licensed under the ISC License.
