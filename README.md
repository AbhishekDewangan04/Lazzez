# 🍽️ Lazzez — Smart Restaurant Web App

**Lazzez** is an AI-powered food ordering platform for a Raipur-based restaurant. Built using **React**, **Vite**, and **Firebase**, it lets users sign in with Google, browse the menu, and place orders. If you're unsure what to eat, Lazzez helps by recommending dishes based on your mood using AI.

---

## 🚀 Features

- 🔐 Google Sign-In (Firebase Authentication)
- 🧠 AI-based food recommendations based on mood
- 🛒 Online ordering with a dynamic menu
- 🔥 Fast and responsive UI (React + Vite)
- ☁️ Firebase integration for database and hosting
- 📱 Mobile-friendly design

---

## 🛠️ Tech Stack

- **Frontend:** React + Vite
- **Authentication:** Firebase Auth (Google Sign-In)
- **Database:** Firebase Firestore
- **Hosting:** Netlify
- **Payment:** RazorPay

---

## 📦 Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/AbhishekDewangan04/Lazzez.git
cd Lazzez
npm install
```

## 🔐 Environment Variables

To run this project, create a `.env` file in the root directory and add your Firebase and Gemini API credentials as shown below:

```env
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_firebase_app_id

VITE_GEMINI_API_KEY=your_gemini_api_key
VITE_RAZORPAY_API_KEY=your_razorpay_api_key
```


## 🧪 Development

To run the app locally with hot reload:

```bash
npm run dev
```
## 📄 License

Licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and share with attribution.

## 👨‍💻 Author
Built with ❤️ by Abhishek Dewangan
