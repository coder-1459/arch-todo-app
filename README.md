# Arch - Todo Schedule Planner

A comprehensive Flutter-based productivity app that helps you stay organized and focused in today's fast-paced world.

## Features

### Task Management
- Create, edit, and organize tasks with categories
- Priority marking for important tasks
- Due date tracking and reminders
- Task completion tracking with visual indicators

### Calendar Integration
- View tasks by date
- Daily task overview
- Calendar-based planning interface

### Productivity Analytics
- Real-time productivity statistics
- Task completion rates
- Weekly and overall progress tracking
- Performance insights

### Built-in Pomodoro Timer
- 25-minute focus sessions
- 5-minute break intervals
- Custom timer options
- Productivity technique integration

### Secure Authentication
- Firebase Authentication
- Google Sign-In integration
- Email/password login
- Secure user data management

### Modern UI/UX
- Beautiful glassmorphism design
- Dark/Light theme support
- Smooth animations and transitions
- Intuitive navigation

### Cross-Platform Support
- Android (Primary)
- iOS ready
- Web compatible
- Desktop support

### Smart Notifications
- Local notification system
- Important task reminders
- Customizable notification intervals
- Background task scheduling

## Technical Stack

- **Frontend:** Flutter & Dart
- **Backend:** Firebase (Auth, Firestore)
- **Local Storage:** Hive database
- **Authentication:** Google Sign-In
- **Notifications:** Flutter Local Notifications
- **State Management:** Flutter built-in state management
- **UI Components:** Custom widgets with Material Design

## Screenshots

![App Screenshot 1](flutter_01.png)
![App Screenshot 2](flutter_02.png)
![App Screenshot 3](flutter_03.png)
![App Screenshot 4](flutter_10.png)

## Getting Started

### Prerequisites
- Flutter SDK (3.8.1 or higher)
- Dart SDK
- Android Studio / VS Code
- Firebase project setup

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/arch-todo-app.git
   cd arch-todo-app
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Create a Firebase project
   - Add your `google-services.json` file to `android/app/`
   - Configure Firebase Authentication

4. **Run the app**
   ```bash
   flutter run
   ```

## Building APK

### Debug APK
```bash
flutter build apk --debug
```

### Release APK
```bash
flutter build apk --release
```

APK files will be generated in:
- Debug: `build/app/outputs/apk/debug/app-debug.apk`
- Release: `build/app/outputs/apk/release/app-release.apk`

## Configuration

### Firebase Setup
1. Create a new Firebase project
2. Enable Authentication (Email/Password and Google Sign-In)
3. Download `google-services.json` and place it in `android/app/`
4. Configure Firebase in your project

### Local Storage
The app uses Hive for local storage. Data is automatically managed and synchronized.

## Key Highlights

- **Offline-first approach** for reliable performance
- **Real-time synchronization** with cloud storage
- **Responsive design** that adapts to different screen sizes
- **Performance optimized** for smooth user experience
- **Modern architecture** following Flutter best practices

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Developer

**Riju Ranjan**
- Email: rijuranjan087@gmail.com
- GitHub: [Your GitHub Profile]

## Acknowledgments

- Flutter team for the amazing framework
- Firebase for backend services
- The Flutter community for support and resources

---

**Made with ❤️ using Flutter**
