

```markdown
# 🚀 SnakesLabs MeetingHub  
### 🏆 Hackathon Winning Project (PSG IdeaQuest’25)

A **real-time distributed video conferencing platform** built using **WebRTC, Flask, and WebSockets**, enhanced with **AI-powered meeting intelligence** for smarter collaboration and productivity.

---

## 🎯 Key Highlights

- ⚡ Ultra-low latency (<200ms) real-time communication  
- 🌐 Distributed WebRTC multi-peer architecture  
- 🤖 AI-powered meeting insights (summary, sentiment, action items)  
- 👥 Supports 5+ concurrent participants  
- 🏆 Recognized as a **Hackathon Winning Project**

---

## 🎯 Features Overview

### 🟢 Track A – Core Communication

- 📹 1-to-1 and Multi-peer WebRTC video conferencing  
- 🔌 WebSocket-based signaling using Flask + Socket.IO  
- 🌍 Cross-device room join/leave synchronization  
- 🎚️ Adaptive bitrate streaming based on network conditions  
- 🖥️ Screen sharing and media controls  
- 🔄 Real-time network adaptation for stable connections  

---

### 🤖 Track B – AI Engagement & Meeting Intelligence

- 🗣️ Live speech-to-text transcription (Web Speech API)  
- 🧠 AI-powered meeting summarization (Google Gemini)  
- ✅ Automatic action item extraction  
- 😊 Real-time sentiment analysis  
- 👁️ Participant engagement tracking (MediaPipe attention detection)  
- 📊 Meeting insights & analytics dashboard  

---

## 🛠️ Tech Stack

### 🔹 Backend
- Python (Flask)
- Flask-SocketIO
- Eventlet (asynchronous server)
- REST APIs

### 🔹 Frontend
- Vanilla JavaScript
- WebRTC APIs
- Chart.js (visual analytics)

### 🔹 AI & Processing
- Google Gemini API (summarization & insights)
- Web Speech API (transcription)
- MediaPipe (attention detection)

### 🔹 Real-Time Communication
- WebSockets (Socket.IO)
- TCP/IP-based signaling

---

## 🏗️ System Architecture

### 🔹 Core Components

- `server.py` → Main Flask + Socket.IO server  
- `main.js` → WebRTC handling & UI logic  
- `index.html` → Frontend interface  
- `summarizer.py` → AI-based summarization  
- `transcription.py` → Speech-to-text processing  
- `engagement.py` → Attention tracking  
- `sentiment_analysis.py` → Real-time sentiment  
- `network_adaptation.py` → Adaptive streaming  

---

### 🔹 WebRTC Communication Flow

```

Client A ←→ Signaling Server ←→ Client B
↓                              ↓
Direct P2P Connection (Audio/Video)

```

---

### 🔹 AI Processing Pipeline

```

Speech → Transcription → Gemini AI → Summary + Action Items
↓
Sentiment Analysis → Insights

````

---

## 🚀 Quick Start

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
````

---

### 2️⃣ Set Environment Variables (Optional)

```bash
export GEMINI_API_KEY="your-gemini-api-key"
export OPENAI_API_KEY="your-openai-api-key"
```

---

### 3️⃣ Start the Server

```bash
python start_server.py
```

---

### 4️⃣ Open in Browser

```
http://localhost:5000
```

---

## 🎮 Usage Guide

### ▶️ Start a Meeting

* Enter a room name (default: `testroom`)
* Click **Join**
* Share room ID with others

---

### 🤖 Use AI Features

* 📜 Live transcription starts automatically
* 🧠 Click **Generate Summary** for AI insights
* 📊 View analytics in the **Insights tab**
* 💾 Download transcript as text

---

### 🎛️ Controls

* Toggle video/audio
* Screen sharing
* Participant monitoring
* Engagement tracking

---

## 📊 API Endpoints

| Method | Endpoint             | Description             |
| ------ | -------------------- | ----------------------- |
| GET    | `/health`            | Server status           |
| POST   | `/summarize`         | Generate summary        |
| GET    | `/transcript/{room}` | Fetch transcript        |
| GET    | `/engagement/{room}` | Engagement metrics      |
| GET    | `/sentiment/{room}`  | Sentiment analysis      |
| POST   | `/adapt`             | Network recommendations |

---

## 🎨 UI Features

### 💻 Responsive Design

* Desktop: Full dashboard
* Mobile: Optimized layout

### 📡 Real-Time Updates

* Live participant tracking
* Real-time transcript
* Sentiment graphs
* Engagement leaderboard

### ♿ Accessibility

* Keyboard navigation
* Screen-reader support
* High contrast UI

---

## 🔒 Security Considerations

* CORS enabled
* Input validation
* API key protection via environment variables
* HTTPS required for production
* Rate limiting recommended

---

## 🚀 Deployment

### 🔹 Render (Recommended)

1. Push code to GitHub
2. Connect to Render
3. Add environment variables
4. Deploy 🚀

---

### 🔹 Production Best Practices

* Use HTTPS (mandatory for WebRTC)
* Configure TURN servers
* Enable logging & monitoring
* Use load balancing
* Apply rate limiting

---

## 🧪 Testing

### Run Setup Check

```bash
python check_setup.py
```

### Run Tests

```bash
python test_app.py
```

---

## 📈 Performance Metrics

* ⚡ Latency: <200ms
* 👥 Participants: 5+ concurrent users
* 🤖 AI Insight Efficiency: +40% improvement

---

## 📦 Future Enhancements

* SFU architecture for scalability
* Meeting recording & playback
* Mobile application
* End-to-End Encryption (E2EE)
* Advanced analytics dashboard

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

## 📝 License

MIT License

---

## 👨‍💻 Author

**Phoobesh S**
M.Tech Integrated (CSE) – Pre-Final Year

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

```


