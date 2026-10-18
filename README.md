# 🕊️ Solace: You Are Not Alone

> A gentle AI companion for the moments when you feel alone.

Solace is a mobile app that gives people a caring, always-available presence when loneliness and isolation weigh heavy. It pairs a warm, judgment-free AI companion with simple tools for calming the mind and understanding your feelings, so support is there at any hour.

---

## 💛 Why Solace?

Loneliness is one of the quietest struggles people face. Not everyone has someone to talk to at 2 a.m. Solace was built so that no one has to sit with those moments entirely by themselves.

---

## ✨ Features

| Feature | What it does |
|---|---|
| 🌤️ **Mood check-in** | Choose how you feel and get a response that meets you where you are |
| 💬 **AI companion chat** | A private, compassionate conversation powered by Claude from Anthropic |
| 🌬️ **Guided breathing** | Short, calming exercises to ease stress and anxiety |
| 📓 **Journaling** | A safe space to put thoughts into words and notice patterns over time |
| 🕰️ **Session history** | Look back on past conversations and see how far you've come |

---

## 🎯 Who It's For

Anyone who feels lonely, isolated, or simply needs someone to talk to, especially when no one else is around.

---

## 🛠️ Built With

- **Expo / React Native**: one codebase for Android and iOS
- **Anthropic API (Claude)**: powers the AI companion
- **Android Studio**: packaging for Google Play
- An initial **React web prototype** (`solace.html`) that shaped the design

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS)
- [Expo CLI](https://docs.expo.dev/) (`npx expo` works without installing)
- [Android Studio](https://developer.android.com/studio) (for Android builds)
- An **Anthropic API key** from [console.anthropic.com](https://console.anthropic.com)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# 2. Install dependencies
npm install

# 3. Add your API key (see Configuration below)

# 4. Start the app
npx expo start
```

Scan the QR code with the **Expo Go** app on your phone, or press `a` to open an Android emulator.

### Configuration

Create a `.env` file in the project root:

```
ANTHROPIC_API_KEY=your_key_here
```

> ⚠️ **Never commit your API key.** Make sure `.env` is listed in `.gitignore`. For production, route AI requests through your own secure backend instead of shipping the key inside the app.

---

## 📦 Publishing

- **Google Play:** build the Android package with Expo / Android Studio and upload it through the Play Console.
- **Apple App Store:** build the iOS version with Expo and submit through App Store Connect.

---

## 🗺️ Roadmap

- [ ] Google Play release
- [ ] Apple App Store release
- [ ] Secure backend for AI requests
- [ ] Reminders and gentle daily check-ins
- [ ] Mood trends over time

---

## ⚠️ Important Note

Solace offers companionship and emotional support. It is **not** a replacement for professional mental health care or emergency services. If you are in crisis or in danger, please contact local emergency services or a trusted person right away.

---

## 🤝 Contributing

Ideas and improvements are welcome. Open an issue to discuss what you'd like to change, or submit a pull request.

---

## 📄 License

Add your chosen license here (for example, MIT).

---

<p align="center">Made with care, so no one has to feel alone. 🕊️</p>
