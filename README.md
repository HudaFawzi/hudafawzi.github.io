# 📚 Bookshelf App

Bookshelf is a modern Android app that lets you explore, search, and manage a collection of books using data from the Google Books API. With a clean and intuitive interface built using Jetpack Compose, the app makes it easy to browse detailed book information, read previews, and keep track of your reads — **even when you’re offline**.


---

## ✨ Features

- 🔍 Search for books by title, author, or keyword  
- 📖 View detailed information including:
  - Title, subtitle, and description  
  - Author(s), publisher, published date  
  - Page count, language, and country of origin  
  - ISBN, average rating, and preview availability  
- 🌐 Open books in Google Play Books or view them in a browser  
- 📥 Download or read online, if available  
- 💡 Elegant UI using Material Design 3 and Jetpack Compose  
- 📤 Share books with others  
- 🏪 Offline cache with Room + Hilt:  
  - Stores previously viewed books in a local database for offline reading and faster loading  
- 🛠 Hilt for dependency injection, making code more scalable and testable  


---

## 🛠 Tech Stack

- **Kotlin** – Primary language  
- **Jetpack Compose** – Modern UI toolkit  
- **Coroutines** – For async/background tasks  
- **Retrofit** – For API/network calls  
- **Coil** – For loading book cover images  
- **Google Books API** – For accessing book data  
- **Google AdMob** – For showing banner ads  
- **Room Database** – Local cache for offline storage  
- **Hilt** – Dependency Injection   

---

## 📡 API Integration

Bookshelf fetches book data using the [Google Books API](https://developers.google.com/books), which provides access to millions of books, including metadata like titles, authors, and cover images.

---

## 🔐 Privacy Policy

Bookshelf respects your privacy. It does not collect any personally identifiable information.

It uses third-party services like the **Google Books API** to fetch public book data, and **Google AdMob** to display banner ads. These services may collect anonymized data as described in their respective privacy policies.

📄 [View Full Privacy Policy](https://hudafawzi.github.io/bookshelf_app/privacy-policy.html)

---

## 📬 Contact

For questions, suggestions, or feedback:  
📧 [bookshelf.developer@gmail.com]

