# **Convo Sphere**
**Convo Sphere** is a real-time chat application designed for dynamic and responsive conversations. It integrates **Natural Language Processing (NLP)** for live sentiment analysis, allowing users to understand the tone and sentiment of messages in real-time. Built with **Gatsby** and **Firebase** for a fast and scalable experience, Convo Sphere aims to provide a seamless chat platform with robust features like user authentication and a responsive UI.

## **System Architecture**
 ![image](https://github.com/user-attachments/assets/13d34d72-9bcb-4535-b011-8b1a9fc939b4)


The above diagram illustrates the core components and their interactions in the Convo Sphere system:
- **Client Layer (Gatsby)** handles the frontend with Chakra UI components
- **Firebase Services** manage authentication and real-time data
- **NLP Service** processes message sentiment using VADER and TextBlob
- **Continuous Deployment** ensures smooth updates via Vercel

## **Features**
- **Real-Time Chat**: Provides a smooth, real-time messaging experience with Firebase's real-time database.
- **User Authentication**: Supports Google and email-based sign-ins using Firebase Auth. Includes options for guest login and account creation.
- **Sentiment Analysis**: Analyzes message sentiments in real time using NLP libraries (VADER and TextBlob), offering users insights into the tone of their conversations.
- **Responsive UI**: Built with Chakra UI to ensure an adaptable and user-friendly interface across devices.
- **Continuous Deployment**: Hosted on Vercel, with continuous integration for seamless and efficient updates.

## **Technologies Used**

- **Frontend**: Gatsby (React-based framework for static sites)
- **Backend**: Firebase (Real-time database and authentication)
- **NLP Libraries**: VADER and TextBlob (for sentiment analysis)
- **UI**: Chakra UI (for responsive design)
- **Hosting**: Vercel (for deployment and continuous integration)

## **Setup and Installation**

### **Prerequisites**

- **Node.js** and **npm** installed
- Firebase project configured (with Realtime Database and Firebase Authentication enabled)
- Vercel account for deployment (optional)

### **Steps**

- **Clone the repository**:
  ```bash
  git clone https://github.com/suckaaatit/convo-sphere.git
  cd convo-sphere

Install dependencies:

### **Firebase Configuration**

- Go to the Firebase Console and create a new project.
- Enable **Firebase Authentication** (Google and Email/Password providers).
- Enable **Realtime Database** and set up the database rules for read and write access.
- Copy your Firebase configuration and create a `.env` file in the project root:

  ```plaintext
  REACT_APP_FIREBASE_API_KEY=your_api_key
  REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
  REACT_APP_FIREBASE_DATABASE_URL=your_database_url
  REACT_APP_FIREBASE_PROJECT_ID=your_project_id
### **Deployment (Optional)**

- Connect your repository to Vercel and deploy the app for automatic updates with every push.

---

### **Usage**

- **Sign In**: Users can sign in with Google or email, or enter as guests.
- **Chat in Real-Time**: Messages are synchronized in real-time across users.
- **Sentiment Analysis**: Messages are analyzed for sentiment, showing a dynamic mood indicator based on the conversation’s tone.
- **Responsive Design**: Access Convo Sphere from any device with a consistent and responsive interface.

---

### **Project Structure**

- **convo-sphere/**
  - **src/**
    - **components/**
    - **pages/**
    - **styles/**
    - **utils/**
  - **backend/**
    - **nlp/**
    - **server/**
  - **public/**
  - **firebaseConfig.js**
  - **.env**

---

### **Contributing**

- Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

---

### **License**

- This project is licensed under the **MIT License**.

---



### **Backend NLP Setup (VADER & TextBlob)**

- Set up a backend service (e.g., using Flask or Node.js) to handle message sentiment analysis.

- Install VADER and TextBlob libraries:

  ```bash
  pip install vaderSentiment textblob

  
### **Contact**

For any questions or support, please contact:

- **Email**: nakashmha@gmail.com
- **GitHub**: [suckaaatit](https://github.com/suckaaatit)
