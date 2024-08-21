# Demo E-Commerce App

A demo **E-Commerce** application built with Flutter, showcasing modern development practices and key technologies.

## Features
- ✅ **Clean Architecture**: Ensures a scalable and maintainable codebase.
- ✅ **Firebase Integration**: For authentication, real-time database, and push notifications.
- ✅ **BloC Pattern**: Efficient state management with a clear separation of business logic and UI.
- ✅ **Dependency Injection**: Managed with **get_it** for smooth and efficient code management.
- ✅ **Functional Programming**: Leveraged **dartz** for robust error handling and functional constructs.

## 🔗 Project Structure

The project structure follows the principles of Clean Architecture:

- **Presentation Layer**: Handles presenting the app content and triggering events that modify the application state.
- **Domain Layer**: The innermost part of the architecture with no dependencies on other layers, focusing on the core business logic.
- **Data Layer**: Responsible for data retrieval and managing data sources.
```
├── presentation layer/
│ ├── pages/
│ ├── state management/
│ └── widgets/
├── domain layer/
│ ├── entities/
│ ├── repository interfaces/
│ └── use cases/
└── data layer/
├── repositories/
├── data sources/
└── models/
```

## 📂 Folder Structure

The folder structure reflects the organization of the project:
└── lib/
  ├── features/
  │ └── auth/
  │ ├── data/
  │ │ ├── data_sources/
  │ │ ├── models/
  │ │ └── repository/
  │ ├── domain/
  │ │ ├── usecases/
  │ │ ├── entities/
  │ │ └── repository/
  │ └── presentation/
  │ ├── bloc/
  │ ├── widgets/
  │ └── pages/
  ├── config/
  │ ├── theme/
  │ └── routes/
  ├── core/
  │ ├── network/
  │ ├── error/
  │ ├── util/
  │ └── usecases/
  └── main.dart

## 🛠️ Commands & Installation

| Command                  | Description                                     |
|--------------------------|-------------------------------------------------|
| `git clone <repo-url>`   | Clone the repository                            |
| `cd demo-ecommerce-app`  | Navigate into the project directory             |
| `flutter pub get`        | Install project dependencies                    |
| `flutter run`            | Run the application                             |
| `flutter build`          | Build the application for release               |
| `flutter test`           | Run tests in the project                        |

To get started with this project, follow these steps:

1. **Clone the repository**:
   '''bash
   git clone https://github.com/yourusername/demo-ecommerce-app.git
2. **Navigate into the project directory**:
   '''bash
   cd demo-ecommerce-app
3. **Install dependencies**:
   '''bash
   flutter pub get
5. **Run the app**:
   '''bash
   flutter run

## Credits
Inspired by the [Complete Flutter E-Commerce App - Bloc, Clean Architecture, Firebase](https://www.youtube.com/watch?v=OTdRkmmE_Vw) tutorial.

## 👀 Want to Learn More?
Feel free to connect with me on LinkedIn or reach out via email.

- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/yourprofile)
- Email: [your.email@example.com](mailto:your.email@example.com)
