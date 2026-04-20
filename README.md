# 📱 Phonebook Mobile Automation (Appium Core)

A high-end mobile test automation framework for the Phonebook Android application. This project showcases advanced mobile-specific interaction techniques and a highly readable **Fluent Interface** design.

## 🎯 Business Goal
To ensure the seamless performance and reliability of the mobile application across various Android environments, focusing on complex UI interactions and contact data management.

## 🛠 Tech Stack
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Appium](https://shields.io/badge/Appium-662D91?style=for-the-badge&logo=appium&logoColor=white)
![Android](https://shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![UiAutomator2](https://img.shields.io/badge/UiAutomator2-007ACC?style=for-the-badge&logo=android&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FFA500?style=for-the-badge&logo=testng&logoColor=white)
![Gradle](https://shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

## 🏗 Architecture & Design Patterns
- **Fluent Interface POM**: Implementation of method chaining (e.g., `page.typeEmail().typePassword().clickLogin()`) for superior test readability and clean DSL.
- **Advanced TouchActions & Gestures**:
  - **Smart Scrolling**: Implemented a **custom recursive scrolling logic** to handle long dynamic lists in Android, ensuring elements are found regardless of their position.
  - **Precise Swiping**: High-precision implementation of `Swipe` (Remove/Edit) using exact coordinates and durations.
- **Cross-Platform Readiness**: Support for both **Android Emulators** (Nexus 6) and **Real Devices** (Samsung S22).
- **Lombok Integration**: Simplified data handling with `@Builder` patterns.

## 🚀 Getting Started
1. **Prerequisites**: Ensure you have JDK 11+, Appium Server 1.22+, and Android SDK.
2. **Device Setup**: Update `AppiumConfig.java` with your device's `udid` and `platformVersion`.
3. **Clone the repo**:
   ```bash
   git clone https://github.com/Alllmighty/Phonebook-Mobile-Automation-Appium.git
   ```
4. **Run Tests**:
   ```bash
   ./gradlew test
   ```