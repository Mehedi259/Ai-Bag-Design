# AI Bag Design 🎒✨

Welcome to **AI Bag Design**, a cutting-edge Flutter application that allows users to create stunning, custom bag designs powered by Artificial Intelligence!

## 🚀 Features

- **AI-Powered Design Generation:** Simply provide a prompt or upload an inspiration image to generate unique bag designs.
- **Save to Collections:** Keep track of your favorite generated designs and organize them into personal collections.
- **Mockup Viewing:** Preview how your bag designs would look in real life with high-quality mockups.
- **Smooth Navigation:** Seamless user experience with a polished UI, built using `go_router` and custom navigation bars.
- **Responsive Layout:** Perfectly adapted for various screen sizes using `flutter_screenutil`.

## 🛠️ Tech Stack

This project is built using modern frameworks and libraries for the best performance and maintainability:

- **Framework:** [Flutter](https://flutter.dev/) (SDK ^3.10.4)
- **State Management & Utilities:** [GetX](https://pub.dev/packages/get)
- **Routing:** [GoRouter](https://pub.dev/packages/go_router)
- **Networking:** [http](https://pub.dev/packages/http), [socket_io_client](https://pub.dev/packages/socket_io_client)
- **UI & Animations:** 
  - `flutter_screenutil`
  - `google_fonts`
  - `lottie`
  - `shimmer`
  - `awesome_dialog`
- **Image Handling:** `cached_network_image`, `image_picker`, `photo_view`

## 📦 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Flutter SDK (v3.10.4 or higher)
- Android Studio / Xcode

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/AI-Bag-Design.git
   ```
2. Navigate to the project directory:
   ```sh
   cd AI-Bag-Design
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run the app:
   ```sh
   flutter run
   ```

## 📱 App Environment

This app is configured with specific launcher icons and native splash screens using:
- `flutter_launcher_icons`
- `flutter_native_splash`

Run the following commands if you update the splash screen or icons:
```sh
flutter pub run flutter_launcher_icons
flutter pub run flutter_native_splash:create
```

## 📄 License

This project is licensed under the MIT License.
