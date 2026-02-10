# Victorian Whispers

A secure messaging platform for sealed, single-view letters.

Victorian Whispers lets users write private messages, seal them and share them via unique one-time access codes. Once a message is read and closed, it self-destructs - basically permanently deleted from the database.



## 🔐 Features

- One-time message retrieval with automatic deletion after read
- Password-locked letter sealing using secure access codes
- Frontend–backend integration for full message lifecycle
- Minimal, elegant interface with customizable writing experience



## 🛠 Tech Stack

- **Frontend:** React (Vite), Tailwind CSS  
- **Backend:** Node.js, Supabase, Crypto  
- **Deployment:** Vercel (frontend), Render (backend)  



## 📁 Repositories

- **Frontend:** [github.com/H-ERa/frontend_react_vite](https://github.com/H-ERa/frontend_react_vite)  
- **Backend:** [github.com/H-ERa/HERa-backend](https://github.com/H-ERa/HERa-backend)



## 💌 Usage

1. Write your message in the interface  
2. Seal it with a password — a unique access code is generated  
3. Share the code with your recipient  
4. Recipient enters the code and password to view the message  
5. Once closed, the message is permanently deleted

Currently, backend is un-deployed due to Render free tier user limits.
