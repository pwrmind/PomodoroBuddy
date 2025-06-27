# Pomodoro Timer App 🍅⏱️

> A beautiful, feature-rich Pomodoro technique timer with productivity tracking and offline support

[![PWA](https://img.shields.io/badge/PWA-✓-blue?logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)
[![Responsive](https://img.shields.io/badge/Responsive-✓-green)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![LocalStorage](https://img.shields.io/badge/LocalStorage-✓-orange)](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

## 🌟 Features

- 🍅 **Pomodoro Timer** with work/break sessions
- 📊 **Productivity Statistics** with daily/weekly tracking
- 📈 **Interactive Charts** for visualizing progress
- 🌗 **Dark/Light Mode** with automatic preference detection
- 🔔 **Sound Notifications** for session transitions
- ⚙️ **Customizable Settings** (session lengths, breaks)
- 📱 **Mobile-Friendly** responsive design
- 📦 **Offline Support** (PWA capabilities)
- 💾 **Data Persistence** using localStorage

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge, Safari)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pomodoro-timer.git
   ```
2. Open `index.html` in your browser

**OR**

Simply visit the live demo: [Pomodoro Timer Live Demo](https://your-deployment-url.com)

## 🛠️ Technologies Used

- **Frontend**: 
  ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
  
- **Libraries**: 
  ![Chart.js](https://img.shields.io/badge/-Chart.js-FF6384?logo=chartdotjs&logoColor=white)

- **PWA Features**: 
  ![Service Workers](https://img.shields.io/badge/-Service_Workers-4285F4?logo=google-chrome&logoColor=white)
  ![Web App Manifest](https://img.shields.io/badge/-Web_App_Manifest-34A853?logo=google-chrome&logoColor=white)

## 🎨 UI Screenshots

| Light Mode | Dark Mode |
|------------|-----------|
| ![Light Mode](screenshots/light-mode.png) | ![Dark Mode](screenshots/dark-mode.png) |
| **Timer View** | **Statistics View** |
| ![Timer View](screenshots/timer-view.png) | ![Stats View](screenshots/stats-view.png) |

## ⚙️ Configuration

Customize your Pomodoro experience in Settings:

```js
// Default settings
{
  workTime: 25,          // Work session duration (minutes)
  shortBreakTime: 5,     // Short break duration (minutes)
  longBreakTime: 15,     // Long break duration (minutes)
  pomodorosBeforeLongBreak: 4,  // Work sessions before long break
  soundEnabled: true,    // Enable/disable sound notifications
  darkMode: false        // Dark theme preference
}
```

## 📦 PWA Installation

Install as a Progressive Web App (PWA) for native-like experience:

1. Visit the app in Chrome/Edge
2. Click the **Install** button in the address bar
3. Or look for "Add to Home Screen" in browser menu

![PWA Installation](screenshots/pwa-install.png)

## 📊 Data Management

All data is stored locally in your browser using:

- `localStorage` for settings and statistics
- Cache API for offline assets (Service Worker)
- IndexedDB (future implementation)

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## ✉️ Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - your.email@example.com

Project Link: [https://github.com/your-username/pomodoro-timer](https://github.com/your-username/pomodoro-timer)

---

Made with ❤️ and ☕ by [Your Name]