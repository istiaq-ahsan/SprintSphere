# 🏃 SprintSphere

**SprintSphere** is an advanced platform that connects marathon organizers with participants, providing a seamless experience for creating, managing, and participating in marathon events. This full-stack application emphasizes user-friendly design, secure functionality, and efficient data management.

---

## 🌟 Project Overview

SprintSphere simplifies the process of organizing and participating in marathon events. It offers:

- **For Organizers:** Tools to create, manage, and track events.
- **For Participants:** A platform to browse, register, and track applications through personalized dashboards.
- **Security:** Secure authentication and role-based access for a smooth and safe user experience.

---

## 🚀 Live Project Link

Check out the live site: [SprintSphere](https://assignment-11-project-68d98.web.app)

---

## 🛠️ Technologies Used

### Frontend

- **React.js** for dynamic UI development.
- **Tailwind CSS** for responsive styling.
- **Daisy UI** for pre-styled components and polished design.
- **JavaScript (ES6)** for modern JavaScript features.

### Backend

- **Node.js** for server-side development.
- **Express.js** for API routing and middleware.
- **MongoDB** for NoSQL database management.

### Authentication

- **Firebase Authentication** for secure and scalable user authentication.

### Additional Libraries

- **React Router** for seamless navigation.
- **Animate.css** for smooth animations.
- **SweetAlert2** for interactive alerts.

---

## ✨ Core Features

1. **Secure Authentication**

   - Sign up and log in with email and password.
   - Role-based access for participants and admins.
   - Secure private routes for sensitive functionalities.

2. **Explore Marathon Events**

   - Browse a list of upcoming marathons.
   - View detailed event information, including location, date, and organizer details.
   - Receive personalized recommendations.

3. **Marathon Management**

   - Add, update, or delete marathon events.
   - Admin dashboard to manage applicants.
   - Participants can apply, update, or withdraw their applications.

4. **Personalized Dashboard**

   - **Participants:** Track registrations and application statuses.
   - **Admins:** View and manage applicants for their events.

5. **Real-Time Updates**
   - Instant updates on event changes and application statuses.
   - Notifications for important actions.

---

## 📦 Dependencies Used

### Frontend

- `react`, `react-dom`, `react-router-dom`
- `tailwindcss`, `daisyui`
- `animate.css`, `sweetalert2`
- `firebase`

### Backend

- `express`, `mongoose`, `cors`
- `firebase-admin`

---

## 🛠️ How to Run the Project Locally

Follow these steps to set up and run the project on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/sprintsphere.git
   cd sprintsphere
   ```
2. **Install Frontend Dependencies**:
   ```bash
   cd frontend
   npm install
   ```
3. **Install Backend Dependencies**:
   ```bash
   cd ../backend
   npm install
   ```
4. **Set Up Environment Variables:**:
   **_Create a .env file in the backend folder and add the following: _**
   MONGO*URI=your_mongodb_connection_string
   FIREBASE_API_KEY=your_firebase_api_key
   STRIPE_SECRET_KEY=your_stripe_secret_key
   \*\*\_Create a .env file in the frontend folder and add the following: *\*\*
   REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
   REACT_APP_BACKEND_URL=http://localhost:5000
5. **Run the Backend Server:**:
   cd ../backend
   npm start
6. **Run the Frontend Development Server:**:
   cd ../frontend
   npm start
7. **Access the Application:**
   Open your browser and navigate to http://localhost:5173.

---

## 🖥️ Live Link to the Deployed Project

[Visit SprintSphere Live Site](https://assignment-11-project-68d98.web.app)

---

## 🌟 Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to submit a pull request.

---

## 📧 Contact

For any inquiries or support, contact us at: **ahsanistiaq23@gmail.com**
