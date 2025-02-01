# Outpass Management System

## Overview
The **Outpass Management System** is designed to streamline the process of requesting and approving outpasses for students in educational institutions. This system eliminates inefficiencies associated with traditional paper-based outpass approvals, making it easier for students to submit requests and for administrators to manage them efficiently.

## Features
- **Student Portal:** Allows students to submit outpass requests online.
- **Approval Workflow:** Automated workflow for faculty and administrative staff to review and approve requests.
- **Notification System:** Real-time notifications for request status updates via email or SMS.
- **History and Reports:** Maintains a history of all requests and approvals with reporting capabilities.
- **Security and Access Control:** Role-based access ensures only authorized personnel can approve requests.
- **Mobile Compatibility:** Accessible through mobile devices for on-the-go access.

## Technologies Used
### **Frontend:**
- HTML, CSS, JavaScript
- React.js (Bootstrapped with [Create React App](https://create-react-app.dev/))

### **Backend:**
- Node.js
- Express.js
- MongoDB

### **Authentication:**
- JSON Web Tokens (JWT)

### **Hosting and Deployment:**
- AWS

## Installation & Setup
### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps to Run Locally
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-repository/outpass-management-system.git
   cd outpass-management-system
   ```
2. **Install Dependencies:**
   ```sh
   npm install
   ```
3. **Set Up Environment Variables:**
   Create a `.env` file in the root directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```
4. **Run the Application:**
   ```sh
   npm start
   ```
5. Open your browser and visit `http://localhost:3000`.

## Available Scripts
In the project directory, you can run:

### `npm start`
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload when changes are made.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Builds the app for production, minifies files, and optimizes for best performance.

### `npm run eject`
Removes Create React App configurations, giving full control over setup.

## Expected Outcomes
- **Increased Efficiency:** Faster processing of outpass requests.
- **Enhanced User Experience:** A user-friendly interface for students and staff.
- **Improved Record Keeping:** Digital records that are easily accessible and searchable.
- **Better Compliance:** Ensures all requests follow institutional policies.
- **Positive Impact on Administration:** Automates routine tasks, freeing up administrative resources.

## Contributors
- **Shravani Wange** - IIT2023222@iiita.ac.in
- **D. Sai Chithra** - IIB2023501@iiita.ac.in
- **Shreeyanshi Gupta** - IIT2023503@iiita.ac.in
- **Aditi Maurya** - IIB2023006@iiita.ac.in
- **Tanisha** - IIB2023029@iiita.ac.in

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries or contributions, feel free to contact any of the contributors listed above.
