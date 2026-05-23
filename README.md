# NavigationDrawerDemo

[![Android Build](https://img.shields.io/badge/Platform-Android-brightgreen.svg)](https://developer.android.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A clean and professional demonstration of an Android application implementing a **Navigation Drawer** (Side Menu) using modern Material Design components and Fragment management.

## 📱 Features

- **Material Design Navigation Drawer:** Seamless side menu integration using `NavigationView` and `DrawerLayout`.
- **Fragment Management:** Dynamic switching between multiple fragments (`BlankFragment`, `BlankFragment2`, and `FragmentList`) without reloading the Activity.
- **Custom Toolbar:** Integration with `androidx.appcompat.widget.Toolbar` for a consistent UI experience.
- **ListFragment Implementation:** Showcases how to display interactive lists within the navigation architecture.
- **Responsive Design:** Handles back-press events to close the drawer and fits system windows correctly.

## 🚀 Getting Started

### Prerequisites

- Android Studio Flamingo | 2022.2.1 or newer
- Android SDK Level 34 (Target SDK)
- Gradle 8.0 or newer

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sultan-zd/Lab10-NavigationDrawerDemo.git
   ```
2. Open the project in **Android Studio**.
3. Let Gradle synchronize and build the project.
4. Run the app on an emulator or physical device.

## 🛠 Tech Stack

- **Language:** Java
- **UI Framework:** Jetpack (AppCompat, ConstraintLayout, Fragment)
- **Design:** Material Components for Android
- **Build System:** Gradle (Kotlin DSL)

## 📂 Project Structure

- `MainActivity.java`: The core activity handling the Drawer layout and Fragment transactions.
- `FragmentList.java`: Implementation of `ListFragment` to demonstrate list data handling.
- `res/layout/`:
    - `activity_main.xml`: Main layout containing `DrawerLayout` and `NavigationView`.
    - `nav_header_main.xml`: The header view for the navigation side menu.
    - `content_main.xml`: The main content area where fragments are hosted.
- `res/menu/`:
    - `activity_main_drawer.xml`: Definition of the menu items for the side drawer.

## 📸 Screenshots

| Navigation Drawer | Fragment List |
|:---:|:---:|
| ![Drawer](https://via.placeholder.com/200x400?text=Drawer+UI) | ![List](https://via.placeholder.com/200x400?text=List+Fragment) |

*(Replace with actual screenshots from your project)*

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
Developed by [Sultan-zd](https://github.com/Sultan-zd)
