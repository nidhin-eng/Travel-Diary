# Travel-Diary
Travel Diary – MERN Stack Web App
Travel Diary is a full-stack social media platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to document and share their travel experiences, similar to Instagram.

It enables users to register/login, create posts with descriptions and images, interact through likes and comments, and securely manage their content.

 Features
1.User Authentication
Register and login securely using JWT (JSON Web Tokens).

Passwords are hashed using bcrypt for security.

2.Post Creation & Feed
Users can create new travel posts with a title, description, and image.

All posts are displayed in a reverse-chronological feed.

Each post includes the author's name, timestamp, image, and interaction options.

3. Interactions
Users can like or unlike posts.

Users can comment on any post to share thoughts or experiences.

Real-time UI updates for likes and comments using React state management.

4.User Profiles
Each user has a profile page showing their posts and profile details.

Profile-specific routes implemented for content isolation.

5.Fontend (React.js)
Built using React.js with component-based architecture.

Responsive design using CSS and flex/grid layouts.

Clean and minimalistic UI for a smooth user experience.

6. Backend (Node.js + Express.js)
RESTful API built with Express.js.

Routes for user authentication, posts, likes, and comments.

MongoDB as the database, connected using Mongoose.

live Demo-https://travel-diary-web.vercel.app/why
