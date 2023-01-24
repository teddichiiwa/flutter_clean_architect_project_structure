# ✨ Flutter Clean Architecture Project Structure

## 👋 Welcome to the Flutter Clean Architecture Project Structure

This project is designed to provide a clean and organized structure for building Flutter applications. The architecture is based on the Clean Architecture principles, which separates the concerns of the application into distinct layers. This makes it easy to maintain, test, and scale the application as it grows.

👉 The project structure is divided into five main layers:

- Application: Entry point of the application, contains the main function and the composition root.
- Core: contains the classes and interfaces that are shared among the layers.
- Domain: Contains the business logic and entities of the application.
- Infrastructure: Handles the communication with external sources of data, such as APIs or databases.
- Presentation: Responsible for handling the user interface and user interactions.

Each layer has its own folder, making it easy to find and modify the code related to that specific layer. Additionally, the project uses dependency injection to handle the dependencies between the different layers, making it easy to test and maintain the code.

I hope you find this project structure helpful in building your own Flutter applications. If you have any questions or feedback, please feel free to reach out to me. Happy coding! ❤️🧡💚

## 🔖 My packages

|Name|Description|
|---|---|
|[vm_lint](https://github.com/teddichiiwa/vm_lint)|🤬 Strict linter for Dart/ Flutter project|
|[melos_template](https://github.com/teddichiiwa/melos_template)|📝 A Melos template for manage multiple packages|
|[native_image](https://github.com/teddichiiwa/native_image)|🌁 A flutter plugin for handling images on iOS and Android
