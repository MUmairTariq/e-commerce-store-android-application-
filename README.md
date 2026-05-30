# E-Commerce Store Android Application

A complete Android e-commerce application with essential features for users.

## ✨ Features Included

### 1. **User Authentication**
   - User Registration & Login
   - Password security with local database
   - User profile management

### 2. **Product Browsing**
   - Browse all products with images and prices
   - Product categories (Electronics, Accessories, etc.)
   - Product search functionality
   - Product ratings and reviews
   - Detailed product information

### 3. **Shopping Cart**
   - Add/remove products from cart
   - Update product quantities
   - View cart total price
   - Persistent cart storage

### 4. **Checkout & Orders**
   - Complete checkout process
   - Multiple payment methods (Card, Cash on Delivery, Wallet)
   - Shipping address management
   - Order history tracking
   - Order status updates (Pending, Shipped, Delivered)

### 5. **User Profile**
   - Edit personal information
   - View order history
   - Manage shipping addresses
   - Update profile settings

### 6. **Search & Filter**
   - Real-time product search
   - Filter by category
   - Sort by price and rating

### 7. **Navigation**
   - Bottom navigation with Home, Category, Search, and Profile tabs
   - Easy navigation between screens
   - Toolbar with cart icon

## 🛠️ Tech Stack

- **Language**: Kotlin
- **Architecture**: MVVM with Repository Pattern
- **Database**: Room Database
- **UI**: Android Material Design
- **Async**: Coroutines & Flow
- **Image Loading**: Glide

## 📁 Project Structure

```
app/
├── data/
│   ├── dao/              # Database DAOs
│   ├── models/           # Data models
│   ├── database/         # Room Database
│   └── repository/       # Repository layer
├── ui/
│   ├── fragments/        # App fragments
│   ├── adapters/         # RecyclerView adapters
│   └── activities/       # App activities
├── viewmodel/            # ViewModels
└── MainActivity.kt       # Entry point
```

## 🚀 Getting Started

### Prerequisites
- Android Studio Arctic Fox or higher
- Android SDK 24 or higher
- Kotlin 1.9+

### Installation

1. Clone the repository:
```bash
git clone https://github.com/MUmairTariq/e-commerce-store-android-application-.git
```

2. Open in Android Studio

3. Sync Gradle files

4. Run on emulator or device

## 📱 App Screens

1. **Login Screen** - User authentication
2. **Home Screen** - Featured products
3. **Category Screen** - Browse by category
4. **Search Screen** - Search products
5. **Product Detail** - View detailed information
6. **Shopping Cart** - Review cart items
7. **Checkout** - Complete purchase
8. **Profile** - User account management

## 💾 Sample Data

The app comes with sample products:
- Wireless Headphones
- Smartphone Case
- USB-C Cable
- Screen Protector

## 🔐 Security

- Local password storage in Room database
- User session management
- Data validation on all inputs

## 📝 Database Schema

- **users** - User information
- **products** - Product catalog
- **cart_items** - Shopping cart
- **orders** - Order history

## 🎨 Customization

You can easily customize:
- Colors in `colors.xml`
- Strings in `strings.xml`
- Add more categories in CategoryFragment
- Update sample products in HomeFragment

## 📞 Support

For issues or feature requests, please open an issue on GitHub.

## 📄 License

This project is open source and available under the MIT License.
