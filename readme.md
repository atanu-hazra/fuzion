# Fuzion: Full-Stack Social Media App

## Description
Fuzion is a full-stack social media application that combines the features of popular platforms like YouTube and Twitter (X), offering hybrid functionality. It allows users to upload and interact with videos, tweets, and playlists. The platform includes advanced features like liking, saving, following, commenting, exploring content, and managing multimedia. Additionally, it provides user authentication, dark/light mode toggle, and responsive design for seamless access across devices.

## Check it Live
You can check the live version of the app here: [Fuzion Live](https://fuzion-media.vercel.app/)

## Features

### **User Features**
- **Authentication**: User registration and login, with JWT-based authentication.
- **Forgot Password**: Users can reset their password via email.
- **Dark/Light Mode**: Toggle between dark and light modes for a personalized user experience.
- **Responsive Design**: Fully responsive layout that adapts to various screen sizes.
  
### **Video Features**
- **Upload Videos**: Upload videos with associated thumbnails.
- **Like Videos**: Like or unlike videos.
- **Add/Remove Videos to/from Playlists**: Manage video playlist.
- **Create, Update, and Delete Videos**: Users can create new videos, update their details, or delete them.
- **Explore Videos**: Search videos you are looking for.
  
### **Tweet Features**
- **Upload Tweets**: Share text-based tweets with optional images (multiple images allowed per tweet).
- **Like Tweets**: Like or unlike tweets.
- **Save Tweets**: Save tweets to a personal collection.
- **Create, Update, and Delete Tweets**: Post, edit, or remove tweets.
- **Comments**: Comment on tweets and videos.
- **Like Comments**: Like or unlike individual comments.

### **Social Features**
- **Follow/Unfollow**: Follow or unfollow other users, check followers and following.
- **View Followers and Followings**: View lists of users who follow you and those you follow.
- **Report Content**: Flag videos, tweets, or comments for review.
  

### **Additional Features**
- **User Profile**: Manage personal profile information, including bio and profile picture.
- **Create and Manage Playlists**: Create playlists, add videos, and delete them.
  
## Tech Stack

- **Frontend**: Next.js, React.js, Tailwind CSS, React Router, Axios, lucide-react, Shadcn UI
- **Backend**: Node.js, Express, MongoDB, Mongoose, JWT Authentication
- **File Storage**: Cloudinary for video and image storage
- **Authentication**: JWT (JSON Web Tokens)
- **State Management**: Redux (for global state management)
- **Form Validation**: React Hook Form with Zod for form validation
- **API Integration**: RESTful API for all features

