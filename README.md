# TODO App

A simple and interactive todo list application built with vanilla JavaScript, HTML, and CSS. Keep track of your tasks with a beautiful user interface and local storage persistence.

## Features

- ✅ **Add Tasks** - Quickly add new tasks to your todo list
- ✏️ **Edit Tasks** - Modify existing tasks easily
- 🗑️ **Delete Tasks** - Remove completed or unwanted tasks
- ✔️ **Mark as Complete** - Toggle task completion status
- 📊 **Progress Tracking** - Visual progress bar showing task completion
- 💾 **Local Storage** - Tasks persist even after closing the browser
- 🎉 **Celebration Effects** - Confetti animation when all tasks are completed

## Demo

![TODO App Screenshot](screenshot.png) _(Add a screenshot of your app here)_

## Technologies Used

- **HTML5** - Structure and layout
- **CSS3** - Styling and animations
- **JavaScript (ES6+)** - Core functionality and logic
- **Local Storage API** - Data persistence
- **tsParticles Confetti** - Celebration effects

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Yashshinde17/TODO-APP.git
```

2. Navigate to the project directory:
```bash
cd TODO-APP
```

3. Open `index.html` in your web browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

## Usage

1. **Add a Task**: Type your task in the input field and click the "+" button or press Enter
2. **Complete a Task**: Click on the task text to mark it as complete/incomplete
3. **Edit a Task**: Click the edit icon (✏️) to modify the task
4. **Delete a Task**: Click the delete icon (🗑️) to remove the task
5. **Track Progress**: Watch the progress bar fill up as you complete tasks

## Project Structure

```
TODO-APP/
│
├── index.html          # Main HTML file
├── style.css           # Styling and layout
├── app.js             # JavaScript logic and functionality
├── img/               # Image assets
│   ├── delete_img.png # Delete icon
│   └── edit_img.png   # Edit icon
└── README.md          # Project documentation
```

## Features in Detail

### Task Management
- Add unlimited tasks to your list
- Each task shows completion status with a checkbox
- Edit existing tasks without losing other data
- Delete individual tasks

### Progress Tracking
- Visual progress bar updates in real-time
- Task counter shows completed/total tasks (e.g., "3/5")
- Percentage-based progress visualization

### Data Persistence
- All tasks are saved to browser's local storage
- Tasks remain after browser restart
- Automatic save on every action

### Celebration
- Confetti animation triggers when all tasks are completed
- Motivational feedback for completing your todo list

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## Future Enhancements

- [ ] Add task categories/tags
- [ ] Due dates and reminders
- [ ] Task priority levels
- [ ] Dark mode toggle
- [ ] Export/Import tasks
- [ ] Search and filter functionality
- [ ] Multiple todo lists

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Yash Shinde**
- GitHub: [@Yashshinde17](https://github.com/Yashshinde17)

## Acknowledgments

- Confetti effects powered by [tsParticles](https://particles.js.org/)
- Icons and design inspiration from various sources

---

⭐ If you found this project helpful, please give it a star!
