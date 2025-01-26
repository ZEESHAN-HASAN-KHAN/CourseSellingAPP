# Classify Course Selling App

![Application Screenshot 1](https://github.com/user-attachments/assets/f536aaf6-fb2b-4d94-a6df-48ae8859fc1a)
![Application Screenshot 2](https://github.com/user-attachments/assets/493cfd51-c244-4c09-adfc-0c8435f4f166)

## Overview
The **Classify Course Selling App** is a platform where users can buy and sell educational courses. This project utilizes the MERN stack (MongoDB, Express.js, React.js, Node.js) to deliver a seamless experience for both buyers and sellers.

---

## Features
- **User Authentication**: Supports user signup/login with token-based authentication.
- **Course Management**:
  - Sellers can create, update, and delete their courses.
  - Buyers can browse and purchase courses.
- **Dynamic Pricing**: Allows sellers to set course prices.
- **Search and Filtering**: Users can search for courses by title or filter by category.
- **Interactive UI**: React.js with Framer Motion for animations.

---

## Tech Stack
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: Vite, EmailJS (for communication), Framer Motion (for animations)

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/classify-course-selling-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd classify-course-selling-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

---

## API Endpoints
### User Authentication
- `POST /api/v1/user/signup`: Register a new user.
- `POST /api/v1/user/login`: Authenticate an existing user.

### Course Management
- `GET /api/v1/courses`: Retrieve a list of courses.
- `POST /api/v1/courses`: Create a new course (requires authentication).
- `PUT /api/v1/courses/:id`: Update a course (requires authentication).
- `DELETE /api/v1/courses/:id`: Delete a course (requires authentication).

---

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact
For any inquiries, please connect with me on [LinkedIn](https://www.linkedin.com/in/zeeshan-hasan-khan-/).

