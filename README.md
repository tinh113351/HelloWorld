# HelloWorld

A base Flutter project for web.

## Getting Started

This project is a starting point for a Flutter web application.

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (>=3.0.0)
- A supported browser (Chrome recommended for development)

### Running the app

```bash
flutter pub get
flutter run -d chrome
```

### Building for production

```bash
flutter build web
```

The output will be in the `build/web` directory.

### Running tests

```bash
flutter test
```

## Project Structure

```
lib/
  main.dart       # Application entry point
web/
  index.html      # Web entry point
  manifest.json   # PWA manifest
test/
  widget_test.dart  # Widget tests
```

## Resources

- [Flutter documentation](https://docs.flutter.dev/)
- [Flutter web support](https://docs.flutter.dev/platform-integration/web)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)