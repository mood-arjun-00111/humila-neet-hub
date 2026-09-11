# 🎯 Humila's NEET Preparation Hub

A comprehensive, interactive NEET preparation dashboard designed to help students organize their study routine, track progress, manage daily tasks, and stay motivated throughout their preparation journey.

## ✨ Features

### 📊 **Dashboard**
- Real-time statistics tracking:
  - Tasks completed today
  - Study sessions completed
  - Subject-wise progress
  - Overall preparation progress

### 📚 **Subject Organization**
- Three core NEET subjects: Physics, Chemistry, and Biology
- Chapter-wise breakdown for each subject
- Quick reference to key topics

### 🎯 **Study Planner**
- Add and manage daily study tasks
- Interactive task list with delete functionality
- Task persistence using LocalStorage
- Clean, intuitive interface

### ⏱️ **Focus Timer (Pomodoro)**
- 25-minute focused study sessions
- Start, pause, and reset controls
- Session tracking
- Automatic alerts when session ends

### 📈 **Progress Tracker**
- Subject-wise progress visualization
- Animated progress bars with gradient design
- Easy percentage input and updates
- Overall progress calculation

### 📝 **Study Notes**
- Write and save important formulas, concepts, and reminders
- Persistent storage across sessions
- Clean textarea for distraction-free note-taking

### 🔥 **Motivation Section**
- Random motivational quotes
- Tailored for NEET preparation
- Click button to get new motivation

### 🌙 **Dark/Light Mode**
- Toggle between dark and light themes
- Theme preference saved locally
- Eye-friendly design for long study sessions

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Storage**: Browser LocalStorage for data persistence
- **Design**: Modern, responsive UI with glassmorphism effects
- **Compatibility**: Works on all modern browsers (Chrome, Firefox, Safari, Edge)

## 🚀 Getting Started

### Option 1: Direct Access
1. Clone the repository:
   ```bash
   git clone https://github.com/mood-arjun-00111/humila-neet-hub.git
   cd humila-neet-hub
   ```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server (recommended):
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     
     # Node.js (with http-server)
     npx http-server
     ```

3. Navigate to `http://localhost:8000` in your browser

### Option 2: Deploy Online
- **GitHub Pages**: Push to GitHub and enable Pages in settings
- **Netlify**: Drag and drop `index.html` at netlify.com
- **Vercel**: Connect GitHub repo and deploy

## 📖 How to Use

### Dashboard
- View your daily statistics at a glance
- Track total tasks, sessions, and overall progress

### Add Study Tasks
1. Navigate to "Today's Study Planner"
2. Type your task (e.g., "Complete 30 Physics questions")
3. Press Enter or click "Add"
4. Delete tasks with the ✕ button

### Use Focus Timer
1. Click "Start" to begin a 25-minute session
2. Click "Pause" to pause the timer
3. Click "Reset" to restart
4. Get alert when session completes

### Track Progress
1. Go to "Preparation Progress" section
2. Enter completion percentage for each subject (0-100)
3. Click "Update" to save
4. View animated progress bars

### Save Notes
1. Click the "Notes" section
2. Write your formulas, concepts, or reminders
3. Click "💾 Save Notes" to persist data

### Get Motivated
- Click "Give Me Motivation" button for random motivational quotes
- Perfect for times when you need a confidence boost

## 💾 Data Storage

All data is stored locally in your browser using **LocalStorage**:
- Tasks: `humilaTasks`
- Progress: `humilaProgress`
- Notes: `humilaNotes`
- Sessions: `humilaSessions`
- Theme: `humilaTheme`

**Note**: Data persists only in the same browser. Clearing browser cache will reset data.

## 🎨 Design Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Glassmorphism**: Modern frosted glass effect in navigation
- **Smooth Animations**: Slide-in effects, hover transitions, and gradient fills
- **Dark Mode**: Eye-friendly interface for extended study sessions
- **Accessibility**: Clean typography, proper contrast ratios, keyboard navigation

## 📱 Mobile Responsive

- Mobile-first approach
- Optimized grid layouts for different screen sizes
- Touch-friendly buttons and inputs
- Full functionality on all devices

## 🔒 Privacy

- **No server storage**: All data stays on your device
- **No tracking**: No analytics or third-party scripts
- **No login required**: Completely anonymous and private

## 🚀 Future Enhancements

- [ ] Cloud sync with Google Drive/OneDrive
- [ ] Mock test tracker
- [ ] Subject-wise question bank
- [ ] Custom timer duration
- [ ] Export progress as PDF
- [ ] Streak counter for consistency
- [ ] Study schedule planner
- [ ] Analytics dashboard

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License.

## 💡 Tips for Success

1. **Consistency Over Perfection**: Study a bit every day rather than cramming
2. **Use the Timer**: 25 minutes of focused study is better than 2 hours distracted
3. **Track Progress**: Seeing progress motivates you to continue
4. **Revision**: Regular revision of concepts solidifies learning
5. **Take Breaks**: Use breaks between sessions to recharge

## ❤️ Support

If you find this helpful, please:
- ⭐ Star this repository
- 🔗 Share with fellow NEET aspirants
- 💬 Provide feedback and suggestions

## 📞 Contact

- **GitHub**: [@mood-arjun-00111](https://github.com/mood-arjun-00111)
- **Issues**: [Report bugs or suggest features](https://github.com/mood-arjun-00111/humila-neet-hub/issues)

---

**Remember**: Your consistent efforts today shape your successful future. 🎯✨

**All the best for NEET! 🚀💪**