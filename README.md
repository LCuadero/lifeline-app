# 🌍 LifeLine: Community Emergency Connect

> Emphasizing humanity, connection, and support — not just tech.

LifeLine is an **AI-assisted emergency response platform** built to help **individuals, community responders, and administrators** coordinate in times of disaster or danger. With a single tap, users can share their location and safety status, while AI provides real-time guidance and comfort.

---

## 🚨 Key Features

### 🧭 For End Users
- “**SafeTag**” emergency button for instant reporting
- Auto-location capture via GPS + reverse geocoding
- Built-in **AI Safety Assistant** that provides calm, verified advice
- Real-time case updates (Pending → Responding → Resolved)

### 🚑 For Responders
- Community-based dashboard showing local reports
- Case filtering (by urgency, type, or location)
- Ability to update victim status (“Rescue dispatched”, “Help delivered”, etc.)

### 🧑‍💼 For Admins
- View and reassign cases across communities
- Generate insights (response time, case frequency, hotspots)
- Broadcast alerts to responders
- Export reports to CSV/PDF

---

## ⚙️ Tech Stack

| Area | Tool | Purpose |
|------|------|----------|
| Frontend | Next.js + TailwindCSS | Fast, responsive UI |
| Backend | Next.js API Routes | Serverless endpoints |
| Database | Supabase | Realtime DB + Auth |
| AI | OpenAI API (GPT-4o-mini) | Chat-based assistance |
| Deployment | Vercel | Seamless serverless deployment |

---

## 🧠 AI Integration

The built-in AI assistant:
- Provides calm, human-like guidance during crises
- Suggests best safety actions based on situation
- Offers general disaster-preparedness tips
- Only gives **verified safety advice** (based on Red Cross / NDCC guidelines)

---

## 🚀 Getting Started

### 1️⃣ Clone the repo
```bash
git clone https://github.com/yourusername/lifeline-app.git
cd lifeline-app
