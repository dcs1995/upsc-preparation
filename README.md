# 🏛️ UPSC Master Preparation App

An interactive, all-in-one web application built to streamline UPSC Civil Services Examination (CSE) preparation. Developed through iterative prompt engineering and interactive design sessions on Google Gemini.

---

## 🌟 Key Features

### 1. 📅 Daily Prelims & Mains Drill
- **Prelims MCQs**: Dynamic practice quizzes categorized by syllabus topics (Polity, History, Economy, Geography, Environment, Science & Tech).
- **Mains Answer Simulator**: Timed prompts with structured rubrics (Introduction, Body/Context, Way Forward) for GS Papers I–IV.
- **Answer Review Helper**: Rubric-based self-evaluation checklist to score mains answers effectively.

### 2. 📰 Daily Current Affairs & Editorial Digest
- Syllabus-mapped daily updates covering **The Hindu** and **The Indian Express**.
- Direct mapping to GS Syllabus heads (e.g., GS-2 Governance, GS-3 Economy & Biodiversity).
- Key takeaways, critical terms, and mind-map summaries for quick revision.

### 3. 🗺️ Interactive Syllabus & Tracker
- Detailed breakdown of both Prelims (GS + CSAT) and Mains (GS I–IV + Essay).
- Visual progress bar and micro-topic revision tracker.
- PYQ (Previous Year Questions) tagging per topic.

### 4. 🧠 Mind Map & Revision Hub
- Topic-wise quick revision cards and mnemonics.
- High-yield tables (Constitutional Articles, Wildlife Sanctuaries, Reports & Indices, Committees).

---

## 🛠️ Tech Stack & Architecture

- **Frontend**: Single-file React / Tailwind CSS (or standalone HTML5/CSS3/Vanilla JS).
- **State Management**: Browser `localStorage` to persist daily quiz scores, notes, and study progress.
- **Icons & Styling**: Tailwind CSS, Lucide icons, responsive layout optimized for desktop and tablet study sessions.
- **Export & Backup**: One-click JSON / Markdown export for study notes and tracked progress.

---

## 🚀 Getting Started

### Option 1: Direct Browser Launch (Single File)
1. Download or copy the generated code file (e.g., `index.html` or `App.jsx`).
2. If it is an HTML bundle:
   - Double-click `index.html` to open it directly in any modern browser (Chrome, Edge, Firefox, Safari).
3. If it is a React/Vite template:
   ```bash
   # Install dependencies
   npm install

   # Start the local development server
   npm run dev
   ```

### Option 2: Run within Gemini Canvas / Live Preview
- The app runs natively inside the Gemini interactive web preview environment without requiring any external server setup.

---

## 📂 Project Structure

```text
├── index.html           # Main application bundle (UI, logic, and styles)
├── README.md            # Project documentation and setup guide
└── assets/              # (Optional) Static icons or syllabus data schemas
```

---

## 🎯 Syllabus Coverage Map

| GS Paper | Focus Areas Covered |
| :--- | :--- |
| **Prelims Paper I** | Current events, Indian History, Geography, Polity, Economy, Ecology/Biodiversity, General Science |
| **Prelims Paper II** | CSAT Comprehension, Reasoning, Basic Numeracy |
| **Mains GS I** | Indian Heritage, History, World Geography, Society |
| **Mains GS II** | Governance, Constitution, Polity, Social Justice, International Relations |
| **Mains GS III** | Technology, Economic Development, Bio-diversity, Security, Disaster Management |
| **Mains GS IV** | Ethics, Integrity, and Aptitude (Case Studies & Ethical Dilemmas) |

---

## 💡 Tips for Customization

- **Add Custom Flashcards**: Edit the embedded data array in the script section to insert custom notes or mnemonics.
- **Change Color Theme**: Modify the Tailwind root color variables to switch to a dark mode or parchment reading theme.
- **Cloud Sync**: Connect the save/load routines to Firebase or Supabase if you wish to study across multiple devices.

---

## 🤝 Contribution & License

Created collaboratively with Google Gemini. Feel free to fork, adapt, and share with fellow UPSC aspirants. Best of luck with your preparation!