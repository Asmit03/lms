# LMS (Flutter)

> A Learning Management System app, built with [Flutter](https://flutter.dev). This repository is currently a fresh Flutter project scaffold — no app-specific screens, features, or backend integration have been implemented yet.

## Status

🚧 **Early scaffold stage.** The repository so far contains only the default output of `flutter create`, with a project name (`lms`) and support for Android, iOS, Web, Linux, macOS, and Windows. Actual LMS functionality (courses, users, auth, content, etc.) has not been built out yet.

This README is written to match that reality, and is meant to be filled in as real features land. Sections below marked *(planned)* are placeholders for you to update.

## Tech Stack

- **Framework:** Flutter (Dart)
- **Platforms targeted:** Android, iOS, Web, Windows, macOS, Linux
- **State management / backend / auth:** *(planned — not yet chosen/implemented)*

## Project Structure

```
lms/
├── android/        # Android platform project
├── ios/            # iOS platform project
├── linux/          # Linux desktop platform project
├── macos/          # macOS desktop platform project
├── web/            # Web platform project
├── windows/         # Windows desktop platform project
├── lib/            # Dart application source code
├── test/           # Automated tests
├── pubspec.yaml    # Project metadata & dependencies
└── analysis_options.yaml
```

## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) installed and on your `PATH`
- A configured platform toolchain for whichever target you're building (Android Studio/SDK for Android, Xcode for iOS/macOS, etc.)
- Run `flutter doctor` to confirm your environment is set up correctly

### Installation

```bash
# Clone the repository
git clone https://github.com/Asmit03/lms.git
cd lms

# Fetch dependencies
flutter pub get
```

### Running the app

```bash
# List available devices/emulators
flutter devices

# Run on a connected device or emulator
flutter run

# Run targeting a specific platform, e.g.
flutter run -d chrome     # Web
flutter run -d windows    # Windows desktop
```

### Running tests

```bash
flutter test
```

### Building for release

```bash
flutter build apk        # Android
flutter build ios        # iOS (requires macOS + Xcode)
flutter build web         # Web
flutter build windows     # Windows
```

## Roadmap *(planned)*

Since this is meant to become a Learning Management System, likely next steps include:

- [ ] Define core user roles (e.g. student, instructor, admin)
- [ ] Authentication & user profiles
- [ ] Course listing, enrollment, and content delivery
- [ ] Assignments/quizzes and grading
- [ ] Backend/API integration (e.g. Firebase, REST API, etc.)
- [ ] State management solution (Provider, Riverpod, Bloc, etc.)
- [ ] UI/UX design and navigation structure

## Contributing

This is currently a small/personal project (forked from [Gautamsam3/lms](https://github.com/Gautamsam3/lms)). If you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Open a pull request

## License

No license file is currently present in this repository. Add a `LICENSE` file to clarify usage terms if you intend for others to use or contribute to this code.

## Acknowledgements

- Forked from [Gautamsam3/lms](https://github.com/Gautamsam3/lms)
- Built with [Flutter](https://flutter.dev)
