# 🍅 Pomodoro Timer

A beautiful, feature-rich Pomodoro Timer built with pure HTML, CSS, and JavaScript. Stay focused and productive with the proven Pomodoro Technique!

![Pomodoro Timer Preview](https://via.placeholder.com/800x400/1a1a1a/ffffff?text=Pomodoro+Timer+Preview)

## ✨ Features

### ⏰ **Timer Functionality**
- **25-minute work sessions** with automatic break transitions
- **5-minute short breaks** after each work session
- **15-minute long breaks** after every 4 work sessions
- **Audio notifications** when sessions complete
- **Start/Pause/Reset** controls with smooth animations

### 📋 **Task Management**
- Add tasks to stay organized during work sessions
- Mark tasks as complete with satisfying animations
- Delete tasks you no longer need
- **Persistent storage** - tasks saved between browser sessions

### ⚙️ **Customizable Settings**
- Adjust work session duration (1-60 minutes)
- Customize short break length (1-30 minutes)
- Set long break duration (1-60 minutes)
- Settings automatically saved to your browser

### 🎨 **Beautiful Design**
- **Dark theme** easy on the eyes for long work sessions
- **Color-coded modes**: Red for work, Green for short breaks, Blue for long breaks
- **Circular progress indicator** with smooth animations
- **Responsive design** works perfectly on desktop and mobile
- **Modern glass-morphism effects** with backdrop blur

## 🚀 Quick Start

### Option 1: Download and Run
1. **Download** the `pomodoro.html` file
2. **Double-click** to open in your web browser
3. **Start focusing!** No installation required

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/pomodoro-timer.git
cd pomodoro-timer
# Open pomodoro.html in your browser
```

## 📖 How to Use

### 🎯 **Getting Started**
1. **Click "Start"** to begin your first 25-minute work session
2. **Add tasks** in the sidebar to track what you're working on
3. **Focus on your work** until the timer completes
4. **Take a break** when the timer switches to break mode
5. **Repeat the cycle** - after 4 work sessions, enjoy a long break!

### ⚡ **Pro Tips**
- **Add tasks before starting** to stay focused on specific goals
- **Use the settings** to adjust timer durations to your preference
- **Don't skip breaks** - they're essential for maintaining productivity
- **Track your sessions** - the header shows your completed session count

## 🛠️ Technical Details

### **Built With**
- **HTML5** - Semantic markup and accessibility
- **CSS3** - Modern styling with animations and responsive design
- **Vanilla JavaScript** - No frameworks, pure performance
- **Web Audio API** - For notification sounds
- **LocalStorage** - Persistent data without a backend

### **Browser Compatibility**
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

### **File Structure**
```
pomodoro-timer/
├── pomodoro.html          # Complete application (HTML + CSS + JS)
├── README.md              # This file
└── LICENSE                # MIT License
```

## 🎨 Customization

### **Changing Colors**
Edit the CSS variables in the `<style>` section:
```css
.header { background: #your-color; }
.timer-display { color: #your-color; }
```

### **Modifying Default Times**
Update the JavaScript variables:
```javascript
let workTime = 25;        // Work session minutes
let shortBreakTime = 5;   // Short break minutes  
let longBreakTime = 15;   // Long break minutes
```

### **Adding New Features**
The code is well-structured and commented. Key functions:
- `toggleTimer()` - Start/pause functionality
- `addTask()` - Task management
- `updateDisplay()` - UI updates
- `playNotificationSound()` - Audio notifications

## 📱 Screenshots

### Desktop View
![Desktop Screenshot](https://via.placeholder.com/600x400/1a1a1a/ffffff?text=Desktop+View)

### Mobile View
![Mobile Screenshot](https://via.placeholder.com/300x500/1a1a1a/ffffff?text=Mobile+View)

### Settings Modal
![Settings Screenshot](https://via.placeholder.com/400x300/1a1a1a/ffffff?text=Settings+Modal)

## 🔧 Troubleshooting

### **Timer Not Starting**
- Check if JavaScript is enabled in your browser
- Ensure you're not in a private/incognito window (affects localStorage)

### **No Sound Notifications**
- Some browsers require user interaction before playing audio
- Click anywhere on the page, then try starting the timer

### **Tasks Not Saving**
- Make sure localStorage is enabled
- Check if you're in private browsing mode
- Clear browser cache if problems persist

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### **Ideas for Contributions**
- 🎵 Custom notification sounds
- 📊 Statistics and productivity tracking
- 🌍 Internationalization (multiple languages)
- 🎨 Additional themes and color schemes
- 📱 Progressive Web App (PWA) features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Francesco Cirillo** for creating the Pomodoro Technique
- **Modern CSS techniques** inspired by contemporary web design
- **Web Audio API** for cross-browser sound notifications
- **The productivity community** for continuous inspiration

## 📞 Support

- 🐛 **Found a bug?** [Open an issue](https://github.com/yourusername/pomodoro-timer/issues)
- 💡 **Have a feature request?** [Start a discussion](https://github.com/yourusername/pomodoro-timer/discussions)
- 📧 **Need help?** Email us at support@yourproject.com

## 🌟 Show Your Support

If this project helped you stay productive, please consider:
- ⭐ **Starring** the repository
- 🔄 **Sharing** with friends and colleagues  
- 💝 **Contributing** to make it even better

---

**Made with ❤️ for productive people everywhere**

*Start your first Pomodoro session today and experience the power of focused work!*
