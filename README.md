# TimeWise — Personal Time Tracking Web App

## Short Description
TimeWise is a **web-based time tracking app** that helps users log daily activities in minutes, visualize how their 24 hours are spent, and analyze productivity. Users can add, edit, and delete activities for each day, view analytics in a chart, and see a “No Data Available” screen when no records exist. The app includes a **demo mode** and is ready for **Firebase integration**.

---

## Live Demo
[Insert Deployed Link Here]

---

## Video Walkthrough
[Insert YouTube / Google Drive Link Here]  

**Video Highlights:**
- Add, edit, delete activities
- Analyse daily activity breakdown with pie chart
- “No Data Available” view
- Demo and Firebase-ready modes
- Use of AI tools in development (UI scaffolding, code generation, helper functions)

---

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Chart.js  
- **Backend/Database:** Firebase Firestore + Firebase Auth (optional)  
- **Deployment:** GitHub Pages / Firebase Hosting  
- **AI Tools Used:** Lovable AI / ChatGPT for UI and code generation

---

## Features
- Add multiple activities per day with category and duration
- Track remaining time (Max 1440 minutes per day)
- Edit and delete activities
- Analyse activities per day with pie chart visualization
- Responsive and clean UI with minimal pastel color palette
- “No Data Available” state with user-friendly message
- Demo mode works without Firebase
- Firebase-ready for real authentication and database syncing

---
## Screenshot
("https://drive.google.com/file/d/1lF-9tfsceGkL2zV2BYisDIx_xpHozjy-/view?usp=sharing")



## How to Run Locally

1. **Clone the repository**  
```bash
git clone <https://github.com/yasaswinireddy119/AI-Powered-Daily-Time-Tracking-Analytics-Dashboard/blob/main/index.html>
cd timewise```

2 .**Open index.html in your browser**

Demo mode works immediately without Firebase.

Optional: Enable Firebase

3.  **Create a Firebase project at Firebase Console**

Enable Authentication (Email/Password or Google)

Enable Firestore Database

Paste your Firebase config into the firebaseConfig object in index.html:

const firebaseConfig = {
  apiKey: "<YOUR_API_KEY>",
  authDomain: "<YOUR_AUTH_DOMAIN>",
  projectId: "<YOUR_PROJECT_ID>",
  storageBucket: "<YOUR_STORAGE_BUCKET>",
  messagingSenderId: "<YOUR_MESSAGING_SENDER_ID>",
  appId: "<YOUR_APP_ID>"
};

## Screenshot
![Alt Text](https://drive.google.com/file/d/1lF-9tfsceGkL2zV2BYisDIx_xpHozjy-/view?usp=sharing)

