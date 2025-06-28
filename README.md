
# ☕ CafeNoor - Android Coffee Ordering App

**CafeNoor** is an elegant and user-friendly coffee ordering Android application. Users can browse through curated coffee categories, view detailed product information, and manage their orders in a cart — simulating a complete coffee shop experience.

---

## 🏗️ Project Structure

```plaintext
CafeNoor/
├── manifests/
│   └── AndroidManifest.xml
│
├── java/
│   └── com.example.myapplication/
│       ├── Adapter/                   # RecyclerView Adapters
│       ├── Domain/                    # Data models (e.g. CoffeeItem)
│       ├── Helper/                    # Utility classes or constants
│       ├── Repository/                # Data source handling
│       ├── ViewModel/                 # ViewModels for MVVM architecture
│       ├── CartActivity.kt            # Displays items in cart
│       ├── DetailActivity.kt          # Coffee item details
│       ├── ItemListActivity.kt        # Grid list of coffee items by category
│       ├── MainActivity.kt            # Home screen with coffee categories
│       └── SplashActivity.kt          # Startup splash screen
│
├── res/
│   ├── drawable/                      # Icons and image assets
│   ├── layout/                        # XML layout files
│   │   ├── activity_cart.xml
│   │   ├── activity_detail.xml
│   │   ├── activity_items_list.xml
│   │   ├── activity_main.xml
│   │   ├── activity_splash.xml
│   │   ├── viewholder_cart.xml
│   │   ├── viewholder_category.xml
│   │   ├── viewholder_item_list.xml
│   │   └── viewholder_popular.xml
│   ├── mipmap/                        # Launcher icons
│   ├── values/                        # Strings, styles, colors
│   └── xml/                           # Additional configurations
````

---

## ✨ Features

* 👋 **Splash Screen**: Displays logo/branding on app launch.
* 📚 **Categories**: Browse coffee types like Espresso, Latte, Cappuccino, etc.
* 📋 **Item Listing**: Grid view with name, image, and price.
* 🔍 **Item Details**: View coffee ingredients, size options, and pricing.
* 🛒 **Cart**: Add/remove items and manage selections.
* 💡 **MVVM Pattern**: ViewModel, Repository, and LiveData based architecture.

---

## 🛠 Tech Stack

| Component    | Tech Used                    |
| ------------ | ---------------------------- |
| Language     | Kotlin                       |
| Architecture | MVVM                         |
| UI           | XML + ViewBinding            |
| Lists        | RecyclerView + ViewHolder    |
| Layouts      | ConstraintLayout, GridLayout |
| State Mgmt   | LiveData + ViewModel         |

---

## 🚀 Getting Started

### 📦 Prerequisites

* Android Studio (Flamingo or later recommended)
* Kotlin plugin
* Emulator or Android device (API 26+)

### 🔧 Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/CafeNoor.git
   cd CafeNoor
   ```

2. Open the project in **Android Studio**

3. Sync Gradle & Build the project

4. Run the app on an emulator or connected device:

   ```bash
   ./gradlew installDebug
   ```

---

## 📸 Screenshots
>
>

* Main Categories Screen
* Coffee Detail Page
* Cart Overview
* App Demo : 

---

## 📈 Future Enhancements

* 🔐 Firebase Auth for login/signup
* 🧾 Order history screen

---

## 🤝 Contributing

Want to contribute? Follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```

---

```
