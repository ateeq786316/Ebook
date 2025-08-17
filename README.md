# 📚 Smart AI Ebook App

A comprehensive React Native application that combines traditional ebook reading with AI-powered content generation, allowing users to create, read, and discover books in an intelligent way.

## 🚀 Overview

Smart AI Ebook App is a full-stack mobile application that revolutionizes the way users interact with digital books. Built with React Native and powered by Google's Gemini AI, it offers a seamless experience for both readers and writers, featuring AI-generated content, customizable templates, and an intuitive user interface.

## ✨ Key Features

### 🔐 Authentication & User Management
- **Secure User Registration & Login** - bcrypt password hashing
- **Password Recovery System** - Email-based OTP verification
- **User Profile Management** - Personalized settings and preferences

### 📖 Reading Experience
- **Multi-format Book Support** - PDF, text, and AI-generated content
- **Category-based Organization** - Fiction, Non-Fiction, Travel, Children's Books, Quran Stories, Urdu Novels
- **Trending Books Discovery** - Popular content recommendations
- **PDF Viewer Integration** - Native PDF rendering with WebView

### ✍️ Writing & Creation
- **AI-Powered Book Generation** - Create books with customizable parameters
- **Smart Templates** - Pre-built structures for different genres
- **Manual Writing Interface** - Traditional text editor with chapter management
- **Content Enhancement** - AI-assisted section generation

### 🤖 AI Integration
- **Google Gemini AI** - Advanced content generation
- **Smart Story Creation** - Generate narratives from titles
- **Content Expansion** - AI-powered chapter development
- **Multi-language Support** - English, Urdu, Spanish, French, German

### 🎨 User Interface
- **Responsive Design** - Optimized for all screen sizes
- **Modern UI/UX** - Material Design principles
- **Dark/Light Themes** - Customizable appearance
- **Intuitive Navigation** - Sidebar and bottom navigation

## 🧑‍💻 Tech Stack

### Frontend
- **React Native** - Cross-platform mobile development
- **Expo** - Development platform and tools
- **React Navigation** - Screen navigation management
- **AsyncStorage** - Local data persistence
- **React Native Vector Icons** - Icon library
- **React Native PDF** - PDF document handling
- **WebView** - Web content rendering

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **Google Gemini AI** - AI content generation
- **Nodemailer** - Email service integration
- **Multer** - File upload handling
- **PDFKit** - PDF generation
- **bcrypt** - Password hashing

### Development Tools
- **Nodemon** - Development server with auto-restart
- **Git** - Version control
- **VS Code** - Code editor

## 🖼️ Screenshots

### App Interface Screenshots

| Splash Screen | Get Started | Login Screen |
|---------------|-------------|--------------|
| ![Splash Screen](https://github.com/user-attachments/assets/bdfb6244-e3d1-4029-b340-b0571ec0a2a1) | ![Get Started](https://github.com/user-attachments/assets/340201f7-d70d-4e1f-abe5-9a6c8c999755) | ![Login](https://github.com/user-attachments/assets/4a32518b-3314-43fa-82f5-8fa68c80bea5) |

| Forget Password | Signup Screen | Choose Mode |
|-----------------|---------------|-------------|
| ![Forget Password](https://github.com/user-attachments/assets/9e2feb2b-bb3f-43db-93f2-53071194004b) | ![Signup](https://github.com/user-attachments/assets/d3a33751-0182-4aa0-ad81-ad7bc41d0212) | ![Choose Mode](https://github.com/user-attachments/assets/e375a5c6-4050-49d4-9017-a6f94d0df5a3) |

| Book Reading | Book Writing | AI Create Book |
|--------------|--------------|----------------|
| ![Book Reading](https://github.com/user-attachments/assets/21a4a84f-f414-43c0-a2e9-5c78ec9533ff) | ![Book Writing](https://github.com/user-attachments/assets/a07fd0e3-c912-43e1-9d49-ac13a1859fdf) | ![AI Create Book](https://github.com/user-attachments/assets/c6742281-8c81-48f0-a814-dcf1b4ec5188) |

| Custom Book | Favorites | Profile |
|-------------|-----------|---------|
| ![Custom Book](https://github.com/user-attachments/assets/c0b321dc-9a1a-4350-9e57-20c1aae282c6) | ![Favorites](https://github.com/user-attachments/assets/a947984e-52fe-4d0d-a704-b267467155fc) | ![Profile](https://github.com/user-attachments/assets/b0bd6b58-9f45-4082-8867-2d5f15da6dd2) |

## ⚙️ Setup Instructions

### 🧑‍💻 Clone the Repository

```bash
# Clone the main project
git clone <repository-url>
cd ebook-app

# Clone the backend server
cd server
git clone <server-repository-url>
```

### 📦 Install Dependencies

#### Frontend (React Native)
```bash
cd ebook
npm install
# or
yarn install
```

#### Backend (Node.js)
```bash
cd server
npm install
# or
yarn install
```

### 🔐 Configure Environment Variables

#### Backend Environment (.env)
```env
# MongoDB Connection
MONGODB_URI=mongodb://127.0.0.1:27017/ebook

# Email Configuration (Gmail)
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-password

# Google Gemini AI API
GEMINI_API_KEY=your-gemini-api-key

# Server Configuration
PORT=3001
```

#### Frontend Configuration (config.js)
```javascript
// Update the API endpoint in ebook/config.js
export const API = "http://your-ip-address:3001";
```

### ▶️ Run the Project

#### Start Backend Server
```bash
cd server
npm start
# Server will run on http://localhost:3001
```

#### Start Frontend App
```bash
cd ebook
npm start
# or
expo start
```

#### Run on Device/Emulator
```bash
# For Android
npm run android

# For iOS
npm run ios

# For Web
npm run web
```

## 📦 Deployment

### Backend Deployment
1. **Environment Setup** - Configure production environment variables
2. **Database Setup** - Set up production MongoDB instance
3. **Server Deployment** - Deploy to cloud platform (Heroku, AWS, etc.)
4. **Domain Configuration** - Set up custom domain and SSL

### Frontend Deployment
1. **Build Generation** - Create production build
2. **App Store Submission** - Submit to Google Play Store and Apple App Store
3. **OTA Updates** - Configure Expo updates for seamless app updates

👥 Team Contributions
## 👥 Developed By
Ateeq ur Rehman
🔹 Role: Full-Stack Developer
🔹 Work: Backend APIs, Auth system, Database integration

Ayesha Shabbir
🔹 Role: Frontend Developer
🔹 Work: UI Design, ReactNative Components.

**Ateeq** - Full Stack Developer
- **GitHub**: [@ateeq-dev](https://github.com/ateeq-dev)
**Ayesha** - Front end Developer
- **GitHub**: [@ayesha-dev](https://github.com/ayesha466)


## 🧠 Challenges Solved

### Technical Challenges
- **Cross-platform Compatibility** - Unified codebase for iOS and Android
- **AI Integration** - Seamless integration with Google Gemini API
- **File Management** - Efficient handling of PDFs and images
- **Real-time Updates** - Dynamic content generation and updates
- **State Management** - Complex state handling across multiple screens

### User Experience Challenges
- **Intuitive Navigation** - Easy-to-use interface for all user types
- **Content Discovery** - Smart categorization and recommendation system
- **Offline Functionality** - Local storage for user preferences
- **Performance Optimization** - Smooth animations and fast loading

### Security Challenges
- **User Authentication** - Secure login and registration system
- **Password Security** - bcrypt hashing and OTP verification
- **API Security** - Protected endpoints and data validation
- **File Upload Security** - Safe file handling and validation

## 🙏 Acknowledgements

- **Google Gemini AI** - For providing the AI content generation capabilities
- **React Native Community** - For the excellent documentation and support
- **Expo Team** - For the amazing development platform
- **MongoDB** - For the robust database solution
- **Open Source Contributors** - For the libraries and tools that made this possible

---

## 📱 App Information

- **Version**: 1.0.0
- **Platform**: iOS, Android, Web
- **Minimum OS**: iOS 12.0, Android 5.0
- **Last Updated**: December 2024

## 🔗 Links

- **Demo**: [App Demo Link]
- **Documentation**: [API Documentation]
- **Support**: [GitHub Issues]

---


⭐ **Star this repository if you find it helpful!**


