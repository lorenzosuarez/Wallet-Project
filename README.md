# Stori Challenge 📱

Welcome to the repository for the Stori Challenge App. This project epitomizes modern Android development, incorporating Material3 design 🎨, Jetpack Compose 🖌️, and a clean architecture 🏗️ that adheres to SOLID principles for a scalable, maintainable, and robust application.

## Project Overview 👀

![Material](https://img.shields.io/badge/Material-Design-blue.svg?style=flat)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-1.4.3-brightgreen.svg?style=flat)
![Kotlin](https://img.shields.io/badge/kotlin-1.7.10-blue.svg?logo=kotlin)
![Firebase](https://img.shields.io/badge/Firebase-BOM%2032.4.0-orange)
![Koin](https://img.shields.io/badge/Koin-DI-green.svg?style=flat)
![Coil](https://img.shields.io/badge/Coil-Image%20Loading-blue.svg?style=flat)
![Lottie](https://img.shields.io/badge/Lottie-Animations-ff69b4.svg?style=flat)
![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-Enabled-green)
![SOLID](https://img.shields.io/badge/SOLID-Principles-blueviolet)


## Features ✨

### User Onboarding and Authentication 🔐

- **Registration**: Users can sign up seamlessly by entering personal data such as name, surname, email, and password.
- **Identification Photo**: As part of the security process, the app allows users to take a photo of their identification.
- **Success Screen**: A congratulatory screen that assures users of their successful account creation.

## Behind the Scenes 🛠️

### Architecture 🏗️

The application follows Clean Architecture guidelines, ensuring that the codebase is maintainable, scalable, and easily testable. The use of MVVM architecture plays a critical role in separating concerns, making the app robust and efficient.

### Firebase Integration 🔥

![Firebase](https://img.shields.io/badge/Firebase-orange?logo=firebase)

- **Firebase Authentication**: Ensures a secure and seamless sign-in experience for the users. It's implemented to manage user authentication, providing options like email/password login, social media login, and more.
  
- **Firebase Cloud Firestore**: Utilized as a scalable and flexible database for the app, storing and syncing user data and banking transactions in real-time across all client apps.

- **Firebase Storage**: Provides a robust solution for storing and serving user-generated content, such as profile pictures, documents, and other media.

- **Firebase Crashlytics**: Integrated to keep track of app stability and monitor and fix issues swiftly. This tool helps in identifying, prioritizing, and tracking the app's stability issues that affect the user experience.
  
## Getting Started 🚀

To clone and run this application, you'll need Git and Android Studio installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/yourusername/stori-challenge.git

# Go into the repository
$ cd stori-challenge

# Install dependencies
$ Android Studio -> Sync Project with Gradle Files

# Run the app
```

## Dependencies 🧰

This project is built using a myriad of modern libraries and tools. Below is a list of the major frameworks and services integrated into the app:

- **Material3**: For a contemporary UI that adheres to the latest Material Design principles.
- **Jetpack Compose**: For a declarative UI that simplifies and accelerates UI development on Android.
- **Clean Architecture**: Ensuring separation of concerns and independence of different app layers.
- **SOLID Principles**: These principles are at the core of the app's design, ensuring each component is easily maintainable and upgradable.
- **Firebase**: For real-time data handling and authentication.

# Demo 🖼️

## 📸 Dark Mode Images

| Splash | Login| Register | Home (empty) |
|---------|---------|---------|---------|
| ![screenshot_splash_dark](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/0cfd25fe-610d-4ea2-af78-b60cf975b317)| ![screenshot_login_dark](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/a747bd1d-96c3-418c-8622-22240a8fc91c) | ![screenshot_register_dark](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/2e7dbac8-fdf3-4d41-a80e-e859df8b29f0) | ![screenshot_home_empty_dark](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/33419fb9-0550-4457-acdf-c30151bf739f) |
| Success register | Home | Details | Logout |
| ![screenshot_success](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/05abaeee-e199-4b0b-a99c-3929ce86f32c) | ![screenshot_home_dark](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/dbd7f603-8cd2-46b7-8367-6abd817f8346) | ![screenshot_details_dark](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/04055d40-dfbf-4f6f-9837-68664d42d9ae) | ![screenshot_logout_dark](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/4cdff116-c8a3-4d5e-aa55-8f23af6a8b9e) |


## 📸 Light Mode Images

| Splash | Login| Register | Home (empty) |
|---------|---------|---------|---------|
| ![screenshot_splash](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/b7055f37-43e6-444f-9c0e-788dcfa67de8) | ![screenshot_login](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/31eba34e-1030-453f-866e-1d3a7f56a0f4) | ![screenshot_register](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/26e2821e-3951-4423-a8c6-a677e839a3d2) | ![screenshot_home_empty](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/04ae4352-fd05-4f7d-bbd1-8e0ab578411f) |
| Success register | Home | Details | Logout |
| ![screenshot_success](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/05abaeee-e199-4b0b-a99c-3929ce86f32c) | ![screenshot_home](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/51194b64-02b5-481f-adee-c0f2fc9c5687) | ![screenshot_details](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/6416eb17-033e-4b40-8d6a-178aec25ccfb) | ![screenshot_logout](https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/ba4349c9-bc8e-4ab2-a429-bb8b4963daea) |




## 🎥 Demo

| Light demo | Dark demo |
|------------|-----------|
| <img src="https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/cdda89d4-80f3-41d5-9c50-9923d512e5b8" width="400"> | <img src="https://github.com/lorenzosuarez/Stori-Challenge/assets/55887438/77e9a1b3-ad57-4640-a0c8-1598d01d5191" width="400"> |


Lorenzo Suarez
