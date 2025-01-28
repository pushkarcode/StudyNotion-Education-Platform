# StudyNotion --> An Online Education Platfrom

# Live_ink - https://studynotion-master.vercel.app/


  ![alt text](image.png)

@StudyNotion
StudyNotion is a full-stack educational platform designed to streamline learning by providing structured courses, easy enrollment, and a reliable review system.

Table of Contents
Features
Tech Stack
Setup
Usage
API Endpoints
Contributing
License
Features

- Course Enrollment: Register and enroll in various courses with ease.
Rating & Reviews: Users can rate courses and leave reviews for others to see.
Swiper Integration: Smooth navigation within course content through Swiper integration.
API-Driven Architecture: Backed by robust RESTful APIs to manage course data, enrollment, and reviews.
- Tech Stack on that
Frontend: React, Redux Toolkit, Tailwind CSS, Swiper
Backend: Node.js, Express
Database: MongoDB (using MongoDB Atlas)
API: RESTful APIs with Express

$Setup
Prerequisites
Node.js & npm installed
MongoDB Atlas account for cloud database
Installation
Clone the repository:

%bash
Copy code
git clone https://github.com/your-username/studynotion.git
cd studynotion
Install dependencies for both frontend and backend:

bash
Copy code
npm install
cd client
npm install
Environment Variables:

In the root folder, create a .env file and add your MongoDB URI, JWT secrets, and other environment-specific variables.
Start the development servers:

Start the backend server:
bash
Copy code
npm run server
Start the frontend server:
bash
Copy code
cd client
npm start
Access the app at http://localhost:3000.

#Usage
Explore courses, enroll, and leave reviews on the platform.
Navigate between lessons with Swiper for an immersive experience.

#Contributing
Contributions are welcome! Please fork this repository and submit a pull request for new features, bug fixes, or enhancements.

#License
This project is licensed under the MIT License. See the LICENSE file for more information.


