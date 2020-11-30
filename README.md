# Fullstack Social Media App  

A fully functional and responsive social media application built using the MERN (MongoDB, Express, React, Node.js) stack. This project includes user authentication, like functionality, dark mode, and an elegant user interface created with Material-UI (MUI).  

## 🚀 Features  
- **User Authentication**: Secure signup and login using JWT.  
- **User Profiles**: Display and edit user profiles with a custom avatar upload.  
- **Posts**: Create, edit, and delete posts with support for likes.  
- **Dark Mode**: Toggle between light and dark themes for better user experience.  
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.  
- **Real-time Updates**: Interactive and smooth user experience.  

## 🛠️ Tech Stack  
- **Frontend**: React.js, Material-UI (MUI), Redux for state management.  
- **Backend**: Node.js, Express.js.  
- **Database**: MongoDB with Mongoose.  
- **Authentication**: JSON Web Tokens (JWT) for secure user login and sessions.  

## 🛠️ Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/yassin549/Social-Media-App-MERN  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd Social-Media-App-MERN 
   ```  

3. Install dependencies for both frontend and backend:  
   ```bash  
   cd client  
   npm install  
   cd ../server  
   npm install  
   ```  

4. Set up environment variables:  
   - Create a `.env` file in the `server` directory.  
   - Add the following variables:  
     ```env  
     MONGO_URI=<your_mongodb_connection_string>  
     JWT_SECRET=<your_jwt_secret_key>  
     ```  

5. Run the development servers:  
   - Frontend:  
     ```bash  
     cd client  
     npm start  
     ```  
   - Backend:  
     ```bash  
     cd server  
     npm start  
     ```  

6. Open your browser and navigate to `http://localhost:3000` to see the app in action.  

## 📂 Project Structure  

```plaintext  
Fullstack-SocialMedia-App/  
├── client/               # Frontend React application  
├── server/               # Backend Express server   
└── README.md             # Project documentation  
```  

## 📝 Contributing  
Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and create a pull request.  

## 🤝 Contact  
For questions or discussions related to this project, contact me at officialyassinkhoualdi@gmail.com.

