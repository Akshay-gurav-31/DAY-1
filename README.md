# 📝 Daily Task Tracker - Premium Edition

A beautiful, modern, and feature-rich task management application built with pure HTML, CSS (Tailwind), and JavaScript. Stay organized, stay productive, and achieve more with this premium task tracker!

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML](https://img.shields.io/badge/HTML-5-orange.svg)
![CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)

## ✨ Features

### 🎨 Premium Design
- **Glassmorphism Effects** - Modern frosted glass UI components
- **Gradient Backgrounds** - Eye-catching purple-to-indigo gradients
- **Smooth Animations** - Slide-in, fade-in, and float animations
- **Custom Scrollbar** - Beautifully styled scrollbar with gradient thumb
- **Responsive Design** - Perfect on mobile, tablet, and desktop

### 🚀 Core Functionality
- ✅ **Add Tasks** - Quick and easy task creation
- ✅ **Mark Complete** - Custom animated checkboxes
- ✅ **Delete Tasks** - Remove individual tasks with confirmation
- ✅ **Filter Tasks** - View All, Active, or Completed tasks
- ✅ **Progress Tracking** - Visual progress bar and statistics
- ✅ **Local Storage** - Tasks persist across browser sessions
- ✅ **Clear Completed** - Bulk remove completed tasks
- ✅ **Reset All** - Clear all tasks with safety confirmation

### 🎯 User Experience
- **Empty State** - Friendly message when no tasks exist
- **Hover Effects** - Interactive feedback on all elements
- **Focus States** - Accessible keyboard navigation
- **Ripple Effects** - Material Design-inspired button animations
- **Stagger Animations** - Tasks appear with sequential delays
- **Real-time Updates** - Instant UI updates on every action

## 🖼️ Screenshots

### Main Interface
The clean and modern interface with gradient backgrounds and glassmorphism effects.
![Main Interface](placeholder)

### Task Management
Add, complete, and manage your daily tasks with ease.
![Task Management](placeholder)

### Progress Tracking
Visual progress indicators keep you motivated throughout the day.
![Progress Tracking](placeholder)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - Pure ES6+ JavaScript, no frameworks
- **LocalStorage API** - Client-side data persistence
- **CSS Animations** - Custom keyframe animations
- **Flexbox & Grid** - Modern CSS layout techniques

## 📦 Installation

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start managing your tasks!

### Option 2: Clone Repository
```bash
git clone https://github.com/Akshay-gurav-31/DAY-1.git
cd DAY-1
# Open index.html in your browser
```

### Option 3: Live Server (Recommended for Development)
```bash
# If you have VS Code with Live Server extension
# Right-click on index.html and select "Open with Live Server"
```

## 🎮 Usage

### Adding a Task
1. Type your task in the input field
2. Click "Add Task" or press Enter
3. Your task appears in the list instantly

### Managing Tasks
- **Complete**: Click the checkbox to mark as done
- **Delete**: Click the "Delete" button (appears on hover)
- **Filter**: Use "All", "Active", or "Completed" buttons

### Bulk Actions
- **Clear Completed**: Remove all completed tasks at once
- **Clear All Tasks**: Reset the entire task list (with confirmation)

## 🎨 Customization

### Colors
The app uses a purple-indigo gradient theme. To customize:

```css
/* Main gradient */
.premium-gradient {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

/* Checkbox gradient */
.custom-checkbox:checked {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Animations
Adjust animation timing in the CSS section:

```css
.animate-slide-in {
    animation: slideIn 0.35s ease-out;
}

.progress-bar {
    transition: width 0.7s cubic-bezier(0.4, 0, 0.2, 1);
}
```

## 🔧 Configuration

### LocalStorage Key
Tasks are stored under the key `premiumDailyTasks`. To change:

```javascript
const TASK_STORAGE_KEY = 'yourCustomKey';
```

### Task Sorting
Tasks are sorted with active tasks first, then by timestamp (newest first).

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

**Note**: Requires a modern browser with ES6+ support and LocalStorage API.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Keep the single-file structure
- Maintain the premium aesthetic
- Add comments for complex logic
- Test on multiple browsers
- Ensure accessibility standards

## 📝 Changelog

### Version 1.0.0 (2026-01-01)
- 🎉 Initial release
- ✨ Premium glassmorphism design
- 🚀 Full task management functionality
- 💾 LocalStorage persistence
- 📊 Progress tracking
- 🎨 Custom animations
- ♿ Accessibility improvements
- 📱 Responsive design

## 🐛 Known Issues

None at the moment! Report issues on the [GitHub Issues](https://github.com/Akshay-gurav-31/DAY-1/issues) page.

## 🔮 Future Enhancements

- [ ] Dark mode toggle
- [ ] Task categories/tags
- [ ] Due dates and reminders
- [ ] Task priority levels
- [ ] Export/Import tasks (JSON)
- [ ] Keyboard shortcuts
- [ ] Task search functionality
- [ ] Drag-and-drop reordering
- [ ] Multiple task lists
- [ ] Cloud sync option

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2026 Daily Tracker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
aUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👨‍💻 Author

**Akshay Gurav**
- GitHub: [@Akshay-gurav-31](https://github.com/Akshay-gurav-31)
- Repository: [DAY-1](https://github.com/Akshay-gurav-31/DAY-1)

## 🙏 Acknowledgments

- Tailwind CSS for the amazing utility-first framework
- Google Fonts for beautiful typography options
- The open-source community for inspiration

## 💖 Support

If you find this project helpful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🔀 Contributing code
- 📢 Sharing with others

---

## ❓ FAQ

**Q: How do I reset my task list?**  
A: You can reset your entire task list by using the "Clear All Tasks" option in the app.

**Q: Can I customize the theme?**  
A: Yes! You can modify the CSS file to adjust colors and animations as per your preference.

**Q: Is there a mobile version?**  
A: The application is responsive and works well on mobile devices.

**Q: How can I contribute to this project?**  
A: Please refer to the contributing section above for guidelines on how you can help.

<div align="center">

**Made with ❤️ for productivity enthusiasts**

[⬆ Back to Top](#-daily-task-tracker---premium-edition)

</div>