# 📄 AI Resume Analyzer

**AI Resume Analyzer** is a smart web application that allows users to upload resumes (PDF format) and get instant analysis on formatting, keyword matching, and score insights.  
The app uses AI-powered evaluation for ATS (Applicant Tracking System) compatibility and provides visual feedback with score indicators.

🔗 **Live Demo:** [ai-resume-analyzer-six-nu.vercel.app](https://ai-resume-analyzer-six-nu.vercel.app/)

---

## ✨ Features

- 📤 **Resume Upload** – Upload PDF resumes for instant processing.
- 🧠 **AI-powered ATS Analysis** – Check keyword match rate, skills presence, and structure compatibility.
- 📊 **Visual Score Indicators** – Score badges, gauges, and circles for better understanding.
- 📜 **Detailed Feedback** – See detailed analysis on how to improve your resume.
- 🛠 **Smooth User Experience** – Built with modern React architecture and Tailwind styling.

---

## 🖼 Folder Structure

```
app/
│
├── components/         # Reusable UI components
│   ├── Accordion.tsx
│   ├── ATS.tsx
│   ├── Details.tsx
│   ├── FileUploader.tsx
│   ├── Navbar.tsx
│   ├── ResumeCard.tsx
│   ├── ScoreBadge.tsx
│   ├── ScoreCircle.tsx
│   ├── ScoreGauge.tsx
│   └── Summary.tsx
│
├── lib/                # Utility & helper functions
│   ├── pdf2img.ts
│   ├── puter.ts
│   └── utils.ts
│
├── routes/             # App pages (React Router)
│   ├── auth.tsx
│   ├── home.tsx
│   ├── resume.tsx
│   ├── upload.tsx
│   └── wipe.tsx
│
├── app.css             # Global styles
└── root.tsx            # Root component
```

---

## 🛠 Tech Stack

- **Frontend Framework:** [React](https://reactjs.org/)
- **Routing:** [React Router](https://reactrouter.com/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **State Management:** [Zustand](https://zustand-demo.pmnd.rs/)
- **File Handling:** [Puter.js](https://puter.com/)
- **PDF Processing:** Custom PDF → Image utility

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/ai-resume-analyzer.git
cd ai-resume-analyzer
```

### 2️⃣ Install Dependencies
```bash
npm install
# or
yarn install
```

### 3️⃣ Run the Development Server
```bash
npm run dev
# or
yarn dev
```

The app will be available at **http://localhost:5173** (Vite default) or your configured port.

---

## 📸 Screenshots

| Resume Upload | ATS Score | Detailed Feedback |
|---------------|-----------|-------------------|
| ![Upload Screen](https://via.placeholder.com/300x180) | ![Score Gauge](https://via.placeholder.com/300x180) | ![Details](https://via.placeholder.com/300x180) |

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and distribute it.

---

## 💡 Contributing

Pull requests are welcome! If you find any bugs or have ideas for improvements, feel free to open an issue.

---