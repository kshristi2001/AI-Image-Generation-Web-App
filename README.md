
# 🧠 AI Image Generation Web App

A full-stack AI-powered image generation application that transforms user prompts into stunning visuals using OpenAI's **DALL·E 3 API**. Built with the **MERN stack** and styled using **Tailwind CSS**, the app provides a sleek and responsive user experience.

---

## 🚀 Features

- 🎨 Generate high-quality images from natural language prompts
- 🧠 Integrated DALL·E 3 API for AI image generation
- 📦 Full-stack MERN architecture (MongoDB, Express.js, React.js, Node.js)
- 📜 "Surprise Me" random prompt generator
- 💾 Download generated images
- 🗃️ MongoDB database to store prompt and image metadata
- 🎨 Responsive UI built with Tailwind CSS
- 🔐 Secure API handling and error feedback

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI Integration**: OpenAI DALL·E 3 API
- **Deployment**: Vercel and Render


## 📂 Folder Structure

```
AI-Image-Generation-Web-App/
├── client/         # React frontend
│   ├── assets/
│   ├── components/
│   └── ...
├── server/         # Express backend
│   ├── routes/
│   ├── controllers/
│   └── ...
└── README.md
```

---

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kshristi2001/AI-Image-Generation-Web-App.git
cd AI-Image-Generation-Web-App
```

### 2. Install dependencies

```bash
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

### 3. Add your OpenAI API Key

Create a `.env` file in the `server/` directory:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the app

```bash
# In server/
npm start

# In client/
npm start
```

The frontend will run at `http://localhost:5173` and the backend at `http://localhost:8080`.

---

## 🧪 Future Enhancements

- User authentication and saved galleries
- Enhanced error handling and loading UI
- Integration with other AI models (e.g., Stable Diffusion)
- Sharing features via social media

---

## 🙌 Acknowledgements

- [OpenAI](https://openai.com/dall-e) – For the powerful image generation API
- [Tailwind CSS](https://tailwindcss.com/) – For beautiful UI design utilities
- [MERN Stack Docs](https://www.mongodb.com/mern-stack) – Full-stack development

---
