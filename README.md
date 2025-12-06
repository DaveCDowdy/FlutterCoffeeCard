# ☕ My Coffee Card - Flutter Application

A simple, interactive mobile application created as the first project in the **Flutter Masterclass (from Novice to Ninja)** course by **The Net Ninja (Shaun Pelling)** on Udemy.

This project focuses on foundational Flutter concepts, including core widgets, state management using `StatefulWidget`, and asset integration.

## ✨ Features

The application is a simple "Coffee Card" that allows a user to customize their coffee preferences.

* **Customizable Preferences:** Use buttons to adjust the coffee **Strength** (via coffee bean icons) and **Sugars** (via sugar cube icons).
* **Stateful Widgets:** Demonstrates basic local **state management** using `setState` to update the UI dynamically.
* **Custom Reusable Widgets:** Uses a custom `StyledBodyText` widget for consistent text styling.
* **Layouts:** Utilizes fundamental layout widgets like `Scaffold`, `AppBar`, `Column`, `Row`, and `Expanded`.
* **Asset Management:** Loads local images for the background, coffee beans, and sugar cubes from the `assets/img/` directory.

## 🚀 Getting Started

### Prerequisites

* **Flutter SDK:** Make sure you have the latest stable version of Flutter installed.
* **Dart SDK:** Included with the Flutter SDK.
* **IDE:** Visual Studio Code or Android Studio with the Flutter and Dart plugins.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/your-repo-name.git](https://github.com/YourUsername/your-repo-name.git)
    cd your-repo-name
    ```
2.  **Get dependencies:**
    ```bash
    flutter pub get
    ```
3.  **Run the app:**
    ```bash
    flutter run
    ```
    (Ensure a device or emulator is connected/running.)

## 📚 Course Context

This project was built while following the highly-rated Udemy course:

* **Course Title:** [Flutter Masterclass (from Novice to Ninja)](https://www.udemy.com/course/flutter-masterclass/)
* **Instructor:** The Net Ninja (Shaun Pelling)
* **Topics Covered in this App:** Flutter basics, widgets, StatelessWidget, StatefulWidget, state management, asset usage, and core layout design.

## 💻 Code Structure

The main logic is contained in the following files:

| File | Description |
| :--- | :--- |
| `lib/home.dart` | The main `StatelessWidget` that sets up the overall screen structure (`Scaffold`, `AppBar`, `Column`). |
| `lib/coffee_prefs.dart` | The `StatefulWidget` containing the preference buttons and logic (`increaseStrength`, `increaseSugars`, and `setState`). |
| `lib/styled_body_text.dart` | A simple `StatelessWidget` used to wrap `Text` widgets with consistent styling. |
| `assets/img/` | Contains the images used in the application (e.g., `coffee_bg.jpg`, `coffee_bean.png`). |

---

## 📄 License

This project is open-sourced under the MIT License.
