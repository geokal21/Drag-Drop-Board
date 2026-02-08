# 📋 Kanban Board

A clean, modern, and interactive Kanban board application built with vanilla HTML, CSS, and JavaScript. Organize your tasks effortlessly by dragging and dropping cards across different workflow stages.


![Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)

## ✨ Features

- **Drag & Drop Interface** - Seamlessly move tasks between columns
- **Three Workflow Columns** - To Do, In Progress, and Done statuses
- **Responsive Design** - Works perfectly on desktop and mobile devices
- **Modern UI** - Clean, minimalist design with smooth animations
- **Visual Feedback** - Hover effects and drag state indicators
- **No Dependencies** - Built with vanilla JavaScript (zero external libraries)

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation or build process required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/drag-drop-board.git
   cd drag-drop-board
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

## 💡 Usage

1. **Adding Tasks** - Tasks are pre-loaded in the "To Do" column
2. **Moving Tasks** - Click and hold a card, then drag it to another column
3. **Organizing** - Release the card to drop it into the desired column
4. **Tracking Progress** - Monitor tasks through To Do → In Progress → Done workflow

### Customizing Tasks

Edit the `index.html` file to add your own tasks:

```html
<div class="list" id="list1">
    <h2>To Do</h2>
    <div class="card" draggable="true" id="card1">Your Task Here</div>
    <div class="card" draggable="true" id="card2">Another Task</div>
</div>
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and drag-and-drop API
- **CSS3** - Flexbox layout, animations, and transitions
- **JavaScript (ES6)** - Event handling and DOM manipulation

## 📁 Project Structure

```
drag-drop-board/
├── index.html      # Main HTML structure
├── style.css       # Styling and responsive design
├── script.js       # Drag & drop functionality
└── README.md       # This file
```

## 🎨 Design Highlights

- **Primary Color**: Deep Blue (`rgb(87, 107, 224)`)
- **Secondary Color**: Teal (`rgb(164, 236, 228)`)
- **Font**: System sans-serif for optimal performance
- **Breakpoint**: Mobile responsive at 768px

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |
| IE 11   | ⚠️ Limited |

## 🔮 Future Enhancements

- [ ] Local storage persistence
- [ ] Add/delete tasks functionality
- [ ] Task editing and descriptions
- [ ] Drag & drop to create new cards
- [ ] Custom color themes
- [ ] Task filtering and search

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. **Fork** this repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Development Guidelines
- Keep code simple and readable
- Add comments for complex logic
- Test across different browsers
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created by **George**

## 🙏 Acknowledgments

- Inspired by popular project management tools
- Built as a learning exercise in vanilla JavaScript
- Special thanks to the web development community

## 📞 Support

Found a bug? Have a suggestion? Please [open an issue](https://github.com/yourusername/drag-drop-board/issues) on GitHub.

---

<div align="center">

**[⬆ back to top](#-kanban-board)**

Made with ❤️ by George

</div>
