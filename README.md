# Flutter REST API Project using Retrofit

This project demonstrates how to make REST API calls in a Flutter application using the Retrofit package for cleaner and more maintainable code.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Setup and Installation](#setup-and-installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to simplify making REST API calls in a Flutter application by leveraging the Retrofit package. Retrofit helps in handling dynamic headers, parameters, requests, and responses in a custom and secure manner.

## Features
- Clean and maintainable code using Retrofit.
- JSON serialization and deserialization.
- Asynchronous data fetching with FutureBuilder.
- Simple UI to display data fetched from API.

## Getting Started
To get started with this project, you need to have Flutter installed on your local machine. Follow the [official guide](https://flutter.dev/docs/get-started/install) to set up Flutter.

## Setup and Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/flutter-retrofit-api.git
   cd flutter-retrofit-api
   ```

2. **Install Dependencies:**
   ```sh
   flutter pub get
   ```

3. **Run the Project:**
   ```sh
   flutter run
   ```

## Project Structure
```
flutter-retrofit-api/
│
├── lib/
│   ├── main.dart
│   ├── services/
│   │   ├── api_service.dart
│   ├── models/
│   │   ├── post_model.dart
│   ├── pages/
│   │   ├── home_page.dart
│
├── pubspec.yaml
```

- **`main.dart`**: Entry point of the Flutter application.
- **`services/api_service.dart`**: Contains the abstract class for Retrofit API calls.
- **`models/post_model.dart`**: Defines the model class and JSON serialization logic.
- **`pages/home_page.dart`**: Contains the UI implementation to display the fetched data.

## Usage

### 1. Add Dependencies
Add the required dependencies in `pubspec.yaml`:
```yaml
dependencies:
  flutter:
    sdk: flutter
  retrofit: ^2.0.0
  dio: ^4.0.0
  json_serializable: ^6.0.0

dev_dependencies:
  build_runner: ^2.1.0
  json_serializable: ^6.0.0
```

### 2. Create API Service
Create an abstract class in `lib/services/api_service.dart`:
### 3. Create Model Class
Define the model class in `lib/models/post_model.dart`:

### 4. Implement the UI
Implement the UI to display the fetched posts in `lib/pages/home_page.dart`:
## Contributing
Contributions are welcome! Please create a pull request with a description of your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy coding! If you have any questions, feel free to open an issue or reach out to the community.