# 📍 LocationApp

LocationApp is an Android application built using **Jetpack Compose** and **Kotlin**. It retrieves the user's current location and displays the latitude, longitude, and address using **reverse geocoding**. The app leverages **Google's Fused Location Provider** for accurate location tracking.

---

## ✨ Features
✅ Request user's current location
✅ Display latitude and longitude
✅ Perform reverse geocoding to get the address
✅ Request location permissions dynamically
✅ Handle permission denial with appropriate messages

---

## 🛠 Technologies Used
- **Kotlin** 🟡
- **Jetpack Compose** 🎨
- **Google Fused Location Provider** 📍
- **Android ViewModel** 📊

---

## 🚀 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Minas-27/LocationApp.git
   ```
2. Open the project in **Android Studio**.
3. Sync Gradle and build the project.
4. Run the application on an **Android emulator** or a **real device**.

---

## 📜 Permissions
Ensure the following permissions are added to `AndroidManifest.xml`:
```xml
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
```

---

## 📖 Usage
1. Launch the app.
2. Click on the **"Get Location"** button.
3. Grant location permissions when prompted.
4. View your **latitude, longitude, and address** on the screen.

---

## 📂 Project Structure
```
📦 com.example.locationapp
 ┣ 📂 ui.theme                # Theme-related files
 ┣ 📜 MainActivity.kt         # Entry point of the app
 ┣ 📜 LocationUtils.kt        # Handles location retrieval & reverse geocoding
 ┣ 📜 LocationViewModel.kt    # Manages location state
 ┣ 📜 LocationData.kt         # Data class for storing location info
```

---

## 🔧 Troubleshooting
- If the location is not displayed:
  - Ensure **GPS is enabled** on your device.
  - Manually grant location permissions in **Settings > Apps > LocationApp > Permissions**.
  - Test on a **real device** instead of an emulator for accurate location retrieval.

---

## 🚀 Future Improvements
- 🗺 **Add a map view** to display the location visually.
- 📡 **Implement background location tracking**.
- ⏳ **Optimize reverse geocoding using coroutines**.

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 🤝 Contributions & Feedback
💡 Contributions and feedback are welcome! Feel free to **open an issue** or **submit a pull request**. 🚀

