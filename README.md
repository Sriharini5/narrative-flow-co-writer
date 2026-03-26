✨📖 Narrative Flow Co-Writer
An AI-powered storytelling application that generates **creative, genre-based stories** using local AI (Ollama + LLaMA3) with strict validation, content control, and immersive UI.

 🚀 Overview

Narrative Flow Co-Writer is a **story-focused AI system** designed to help users:

* Generate creative stories
* Maintain genre consistency
* Control tone and writing style
* Ensure safe and relevant content

Unlike general AI tools, this application strictly focuses on **story generation only**.
🎯 Features
🧠 AI Story Generation

* Powered by **Ollama (LLaMA3)**
* Generates stories based on:

  * Genre
  * Tone
  * Writing Mode
🎭 Genre-Based Storytelling

Supports multiple genres:

* 🪄 Fantasy
* 👻 Horror
* 🚀 Sci-Fi
* 🔍 Mystery

✔ Ensures **strict genre consistency
✍️ Writing Modes

* **Continue** → Extend the story
* **Rewrite** → Recreate the story
* **Enhance** → Improve story quality
🔒 Smart Validation System
Prevents non-story inputs:
* Blocks coding, definitions, etc.
* Ensures only storytelling prompts are accepted
  🛡️ Content Restriction Filter
Blocks:
* Harmful content
* Illegal topics
* Non-story queries (actors, exams, etc.)
   🎨 Dynamic UI Experience

* Animated gradient backgrounds
* Genre-based themes
* Smooth chat interface
 💾 Chat History

* Stores previous chats
* Allows switching between stories
* Maintains story flow
 📥 Download Story

* Export AI-generated story as `.txt` file
🖥️ Offline AI Support

* Runs locally using **Ollama**
* No API cost
* Better privacy
🏗️ Tech Stack

| Component  | Technology      |
| ---------- | --------------- |
| Frontend   | Streamlit       |
| Backend AI | Ollama (LLaMA3) |
| Language   | Python          |
| Storage    | Session State   |

⚙️ Installation

 1️⃣ Install Ollama

Download and install:
👉 [https://ollama.com](https://ollama.com)

 2️⃣ Pull Model

Run in terminal:

```bash
ollama pull llama3
```
 3️⃣ Run Ollama

```bash
ollama run llama3
```
 4️⃣ Install Python Dependencies

```bash
pip install streamlit requests
```

---
5️⃣ Run the App

```bash
streamlit run app.py
```
🔄 Workflow

1. User enters story idea
2. System validates input
3. Restriction check applied
4. Prompt sent to Ollama
5. AI generates story
6. Story displayed
7. Stored in chat history

📊 Comparison with Other AI Systems

| Feature       | Narrative Flow  | ChatGPT    | Gemini   |
| ------------- | --------------  | -----------| -------- |
| Story Focus   | ✅ Yes          | ❌ No     | ❌ No    |
| Genre Control | ✅ Strict       | ⚠️ Weak   | ⚠️ Weak  |
| Validation    | ✅ Strong       | ❌ No     | ❌ No    |
| Offline       | ✅ Yes          | ❌ No     | ❌ No    |
| UI Experience | ✅ Rich         | ⚠️ Basic  | ⚠️ Basic |

⚠️ Limitations

* Only supports story-based input
* Requires Ollama setup
* Depends on system performance

💡 Future Enhancements

* User login system
* Database storage
* Voice-based storytelling
* Multi-language support
* Advanced story memory

📌 Conclusion

Narrative Flow Co-Writer is a **specialized AI storytelling tool** that delivers:

* Controlled content generation
* Immersive user experience
* High-quality narrative output

Perfect for:

* Students
* Writers
* AI projects
* Hackathons

🤝 Contributing

Contributions are welcome! Feel free to fork and improve the project.

 📜 License

This project is for educational and research purposes.

