# 🛍️ E-commerce App

A sleek and functional e-commerce Android application focused on selling shoes. Built using **Kotlin**, **Firebase**, and follows **MVVM (Model-View-ViewModel)** architecture. The app supports user authentication, product browsing, cart management, and order placement.

## 🔧 Tech Stack

- **Language:** Kotlin
- **Architecture:** MVVM
- **Backend:** Firebase (Realtime Database / Firestore, Firebase Auth, Firebase Storage)
- **UI:** XML, Material Components
- **Libraries:**
  - Glide (image loading)
  - Firebase KTX Libraries
  - ViewModel & LiveData
  - Navigation Component
  - Coroutines (optional)

## 🚀 Features

- 👟 **Product Listing** – Browse all available shoes with images, prices, and descriptions.
- 🛒 **Add to Cart** – Select shoe sizes and quantities, then add to cart.
- 👤 **User Authentication** – Sign up and log in with Firebase Authentication.
- 🧾 **Order Placement** – Place orders and view order history.
- 📦 **Product Details** – View product images, ratings, and reviews.
- 🗂️ **MVVM Pattern** – Clean separation of concerns with ViewModel and Repository layers.
- 🌐 **Firebase Integration** – Realtime database for syncing product and order data.

## 📸 Screenshots

*(Add screenshots here)<img width="1440" height="3120" alt="Screenshot_1752680150" src="https://github.com/user-attachments/assets/8c0b1995-e10c-4665-9830-bde7df72965c" />
*<img width="1440" height="3120" alt="Screenshot_1752680141" src="https://github.com/user-attachments/assets/06c8ebd2-3ad2-4505-8d74-604a1634cef1" />

<img width="1440" height="3120" alt="Screenshot_1752680156" src="https://github.com/user-attachments/assets/ec99e408-4929-4ee8-92ed-85a2da89dd76" />

## 🏗️ Project Structure
```bash
com.example.e_commerce
├── activity
│ ├── DashboardActivity.kt
│ ├── CartActivity.kt
│ ├── DetailActivity.kt
│ └── SplashScreenActivity.kt
│
├── adapter
│ ├── ColorAdapter.kt
│ ├── CartAdapter.kt
│ ├── PopularAdapter.kt
│ ├── BrandAdapter.kt
│ ├── PicsAdapter.kt
│ ├── SizeAdapter.kt
│ └── SliderAdapter.kt
│
├── model
│ ├── ItemModel.kt
│ ├── BrandModel.kt
│ └── SliderModel.kt
│
├── viewmodel
│ └── MainViewModel.kt
│
├── repository
│ └── MainRepository.kt
│
├── helper
│ ├── TinyDb.kt
│ ├── ChangeNumberItem.kt
│ └── ManagementCart.kt
│
└── layout
├── activity_dashboard.xml
├── activity_detail.xml
├── activity_cart.xml
├── activity_splash.xml
├── slider_item_container.xml
├── viewholder_brand.xml
├── viewholder_cart.xml
├── viewholder_color.xml
├── viewholder_pics.xml
├── viewholder_recommended.xml
└── viewholder_size.xml

---

## 🔧 Firebase Configuration

1. Go to [Firebase Console](https://console.firebase.google.com/).
2. Create a new project and register your Android app.
3. Download `google-services.json` and place it inside the `/app` folder.
4. Enable the following services:
   - Firebase Authentication (Email/Password)
   - Realtime Database (set appropriate rules)
   - Firebase Storage (optional for image uploads)

---

## 🏁 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-shoes-app.git

---

## 📃 License
This project is licensed under the MIT License. See the LICENSE file for details.


