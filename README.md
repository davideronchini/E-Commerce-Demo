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

## 🗄 Folder Structure

The project folder structure therefore follows the principles of Clean Architecture and is organized as follows:
```
└── lib/
  ├── features/
  │ └── auth/
  │   ├── data/
  │   │ ├── data_sources/
  │   │ ├── models/
  │   │ └── repository/
  │   ├── domain/
  │   │ ├── usecases/
  │   │ ├── entities/
  │   │ └── repository/
  │   └── presentation/
  │     ├── bloc/
  │     ├── widgets/
  │     └── pages/
  ├── config/
  │ ├── theme/
  │ └── routes/
  ├── core/
  │ ├── network/
  │ ├── error/
  │ ├── util/
  │ └── usecases/
  └── main.dart
```

## 🛠️ Commands & Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash git clone https://github.com/yourusername/demo-ecommerce-app.git ```
2. **Navigate into the project directory**:
   ```bash cd demo-ecommerce-app ```
3. **Install dependencies**:
   ```bash flutter pub get ```
4. **Run the app**:
   ```bash flutter run ```

Other commands:

5. **Build the application for release**:
   ```bash flutter build ```
6. **Run tests in the project**:
   ```bash flutter test ```
   
## Credits

This project is inspired by the [Complete Flutter E-Commerce App - Bloc, Clean Architecture, Firebase](https://www.youtube.com/watch?v=OTdRkmmE_Vw) tutorial from the [Flutter Guys](https://www.youtube.com/@flutterguys) YouTube channel. 

A special thanks to the creators for their valuable insights and guidance on implementing clean architecture and advanced Flutter concepts.


## 👀 Interested in Learning More?

If you have any questions, would like to discuss this project further, or are interested in potential collaboration opportunities, please feel free to connect with me through the following channels:

- LinkedIn: [davideronchini](www.linkedin.com/in/davideronchini)
- Email: [ronchinidavid3@gmail.com](mailto:ronchinidavid3@gmail.com)
