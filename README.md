# Bookshelf 📚

A modern, professional Android application for book enthusiasts, built with Jetpack Compose and Material 3. Explore a vast collection of books, manage your personal library, and stay updated with the latest in the literary world.

## ✨ Features

- **Explore & Discover**: Search for books using the Google Books API and discover new titles across various categories.
- **Personal Library**: Save your favorite books to "My Books" for offline access, powered by Room database.
- **Detailed Insights**: View comprehensive details for each book, including descriptions, authors, ratings, and high-quality covers.
- **Professional UI/UX**: Built with Material Design 3 (Material You) for a beautiful, responsive, and personalized experience.
- **Dark Mode Support**: Seamlessly switches between light and dark themes.
- **Stay Notified**: Receive updates and recommendations via Firebase Cloud Messaging.
- **Ad-Supported & Premium**: Includes AdMob integration for sustainability and Google Play Billing for premium features.
- **Search & Filter**: Powerful search functionality helping you find exactly what you're looking for.

## 🛠 Tech Stack

- **UI**: [Jetpack Compose](https://developer.android.com/jetpack/compose) - Modern declarative UI toolkit.
- **Architecture**: MVVM (Model-View-ViewModel) with Clean Architecture principles.
- **Dependency Injection**: [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) - Standard DI library for Android.
- **Database**: [Room](https://developer.android.com/training/data-storage/room) - Robust local data persistence.
- **Networking**: [Retrofit](https://square.github.io/retrofit/) & [Kotlinx Serialization](https://github.com/Kotlin/kotlinx.serialization) - Efficient API communication.
- **Image Loading**: [Coil](https://coil-kt.github.io/coil/compose/) - Lightweight image loading library.
- **Firebase**:
    - **Cloud Messaging (FCM)**: Remote notifications.
    - **Analytics**: User behavior insights.
    - **Crashlytics**: Real-time crash reporting.
    - **In-App Messaging**: Engaging users within the app.
- **Monetization**:
    - **AdMob**: Banner and Interstitial ads.
    - **Google Play Billing**: Seamless in-app purchases.
- **Data Persistence**: [DataStore](https://developer.android.com/topic/libraries/architecture/datastore) - Scalable and modern data storage for preferences.

## 🏗 Architecture

The project follows the recommended Android Architecture guidelines:

- **UI Layer**: Composable functions observing state from ViewModels.
- **Domain Layer**: Contains business logic and repository interfaces (simplified in this project for direct repository access).
- **Data Layer**: Repositories managing data flow between the local database (Room) and the remote API (Retrofit).

## 🚀 Getting Started

### Prerequisites

- Android Studio Koala | 2024.1.1 or newer.
- JDK 17.
- Android SDK 35 (Compile SDK 36).

### Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HudaFawzi/Bookshelf.git
   ```
2. **Open in Android Studio**:
   Import the project into Android Studio.
3. **Firebase Configuration**:
   Add your `google-services.json` file to the `app/` directory.
4. **AdMob ID**:
   Update the AdMob App ID in `AndroidManifest.xml` if necessary.
5. **Build & Run**:
   Sync Gradle and run the app on an emulator or physical device (Min SDK 23).

---
Developed with ❤️ by [Huda Fawzi](https://github.com/HudaFawzi)
