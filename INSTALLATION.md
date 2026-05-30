# Installation Guide

## Step-by-Step Setup

### 1. Requirements
- Android Studio (Latest version)
- JDK 11 or higher
- Android SDK API Level 24+
- 2GB RAM minimum

### 2. Clone Repository
```bash
git clone https://github.com/MUmairTariq/e-commerce-store-android-application-.git
cd e-commerce-store-android-application-
```

### 3. Open in Android Studio
1. Launch Android Studio
2. Click "Open"
3. Select the project folder
4. Wait for Gradle sync to complete

### 4. Configure Project
1. Update `build.gradle.kts` if needed
2. Set target SDK to 34
3. Minimum SDK is 24

### 5. Build & Run

**Option A: Using Android Studio**
1. Click Green Play Button
2. Select Emulator or Device
3. Wait for app to install and run

**Option B: Using Terminal**
```bash
./gradlew build
./gradlew installDebug
```

### 6. First Run
1. App launches with Login screen
2. Click "Don't have account? Sign up" to create account
3. Fill in details and sign up
4. Login with your credentials
5. Explore the app!

## Troubleshooting

### Gradle Sync Failed
- Update Android Studio to latest version
- Check internet connection
- Delete `.gradle` folder and sync again

### Build Errors
- Clean project: Build → Clean Project
- Rebuild: Build → Rebuild Project
- Check SDK versions in `build.gradle.kts`

### Runtime Crashes
- Check Android version (API 24+)
- Grant app permissions if prompted
- Clear app data and reinstall

## Features to Try

1. **Create Account**
   - Sign up with email and password
   - Login with credentials

2. **Browse Products**
   - View featured products on Home tab
   - Click on any product for details
   - Add to cart

3. **Search Products**
   - Go to Search tab
   - Type product name
   - See real-time results

4. **Shopping Cart**
   - Add multiple products
   - Click cart icon to view
   - Adjust quantities
   - Checkout

5. **Place Order**
   - Fill shipping details
   - Select payment method
   - Complete checkout
   - View order in history

6. **Manage Profile**
   - View and edit profile
   - Check order history
   - Logout

## System Requirements

| Component | Version |
|-----------|----------|
| Android SDK | 24+ |
| Gradle | 8.0+ |
| Kotlin | 1.9+ |
| Java | 11+ |

## File Structure After Installation

```
e-commerce-store-android-application-/
├── src/
│   ├── main/
│   │   ├── java/com/example/ecommerce/
│   │   │   ├── data/
│   │   │   ├── ui/
│   │   │   ├── viewmodel/
│   │   │   ├── repository/
│   │   │   └── MainActivity.kt
│   │   ├── res/
│   │   │   ├── layout/
│   │   │   ├── menu/
│   │   │   ├── drawable/
│   │   │   └── values/
│   │   └── AndroidManifest.xml
│   └── test/
├── build.gradle.kts
├── README.md
└── INSTALLATION.md
```

## Next Steps

1. Read `README.md` for features overview
2. Explore the code structure
3. Customize colors and strings
4. Add more products to database
5. Implement backend API integration

## Support

If you face any issues:
1. Check this guide again
2. Look at error messages in Logcat
3. Search GitHub issues
4. Create new issue with details
