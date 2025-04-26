# Photo App Gallery

A modern Flutter application that showcases a beautiful photo gallery with detailed views. This cross-platform app runs on iOS, Android, and macOS, providing a seamless photo browsing experience.

## Features

- Browse photo gallery with thumbnails
- View detailed photo information
- Smooth navigation between gallery and detail views
- Cross-platform support (iOS, Android, macOS)
- Material Design UI with custom styling
- Network image loading with loading indicators
- Error handling for failed image loads

## Screenshots

<p>
<img src="assets/one.png" width=250px hspace="10" alt="Gallery View">
<img src="assets/two.png" width=250px hspace="10" alt="Photo Detail View">
<img src="assets/three.png" width=250px hspace="10" alt="Loading State">
</p>

## Tech Stack

- Flutter SDK (>=3.1.3)
- GetX for state management and navigation
- HTTP package for API integration
- Material Design components

## Getting Started

### Prerequisites

- Flutter SDK (>=3.1.3)
- Dart SDK
- Android Studio / VS Code with Flutter plugins
- iOS development setup (for iOS deployment)
- macOS development setup (for macOS deployment)

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd photo_app
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Dependencies

- flutter: sdk
- cupertino_icons: ^1.0.2
- http: ^1.1.0
- get: ^4.6.6

## Development Setup

1. Open the project in your preferred IDE (Android Studio / VS Code)
2. Ensure Flutter SDK is properly configured
3. Run `flutter doctor` to verify all requirements are met
4. Start coding!

## Build and Deploy

### Android
```bash
flutter build apk --release
```

### iOS
```bash
flutter build ios --release
```

### macOS
```bash
flutter build macos --release
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
