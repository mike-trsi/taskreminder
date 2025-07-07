# Task Reminder Web Application - AI Playground

A responsive task reminder web application built as a test for Warp 2.0 and Codex using HTML, jQuery, and Tailwind CSS that helps you stay organized with smart notifications.

## Features

- ✅ **Add Tasks**: Create tasks with descriptions up to 120 characters
- ⏰ **Flexible Reminders**: Set reminders by specific time or duration from now
- 🔔 **Multi-Modal Notifications**: 
  - Visual notifications in the browser
  - Browser push notifications
  - Audio notifications with pleasant chime sound
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- 💾 **Persistent Storage**: Tasks are saved locally and persist between sessions
- ⏱️ **Real-time Updates**: Live countdown timers for all active tasks
- 🎨 **Modern UI**: Clean, modern design using Tailwind CSS
- 😴 **Snooze Reminders**: Use the "Snooze" button in a reminder notification to delay the task by five minutes

## Technology Stack

- **HTML5**: Semantic structure and modern web standards
- **jQuery**: DOM manipulation and event handling
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Web Audio API**: For audio notifications
- **LocalStorage**: Client-side data persistence

## How to Use

1. **Open the Application**: Simply open `task-reminder.html` in your web browser
2. **Allow Notifications**: Grant permission for browser notifications when prompted
3. **Add a Task**: 
   - Enter your task description (max 120 characters)
   - Choose reminder type:
     - **Specific Time**: Select a time for today (cannot be in the past)
     - **Duration**: Set hours and minutes from now
4. **Manage Tasks**: View all your tasks with live countdown timers
5. **Get Notified**: Receive visual, audio, and browser notifications when reminders are due

## Features in Detail

### Task Management
- Add multiple tasks with unique descriptions
- Real-time character counter with visual feedback
- Input validation to prevent invalid reminder times
- Remove tasks individually with delete button

### Notification System
- **Visual Notifications**: Slide-in notifications with color-coded types
- **Browser Notifications**: Native OS notifications (requires permission)
- **Audio Notifications**: Pleasant two-tone chime using Web Audio API
- **Fallback Support**: Graceful degradation for unsupported browsers
- **Snooze Option**: Click "Snooze" in a reminder notification to postpone that task for another five minutes

### Responsive Design
- Mobile-first approach with Tailwind CSS
- Adaptive layout for different screen sizes
- Touch-friendly interface elements
- Smooth animations and transitions

### Data Persistence
- Tasks automatically saved to browser's localStorage
- Persistent across browser sessions
- Automatic restoration of active reminders on page reload

## Browser Compatibility

- Modern browsers supporting ES6+
- Web Audio API support for audio notifications
- Notification API support for browser notifications
- LocalStorage support for data persistence

## Installation

No installation required! Simply:

1. Download the `task-reminder.html` file
2. Open it in any modern web browser
3. Start adding tasks and reminders

## Development

The application is built as a single HTML file containing all necessary code:
- HTML structure
- CSS styling (Tailwind CSS via CDN)
- JavaScript functionality (jQuery via CDN)

To modify or extend the application, edit the `task-reminder.html` file directly.

## License

This project is open source and available under the MIT License.
