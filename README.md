
# 🚀 Flutter Learning Roadmap

## ✅ Stage 1: Navigation  
**⏳ Timeframe:** 1 Day  
**🎯 Goal:** Implement multi-screen navigation

### 🔹 Mini Tasks:
- [ ] Create two screens and navigate using `Navigator.push()` 🔥
- [ ] Return data using `Navigator.pop()`
- [ ] Use `MaterialPageRoute` with a custom transition
- [ ] Setup named routes via `onGenerateRoute` 🔥
- [ ] Pass arguments between screens

### 📺 YouTube:
- [Navigation Basics](https://youtu.be/YO9dJmBF_j8)
- [Named Routes](https://youtu.be/Ej_Pcr4uC2Q)

### 🌐 Docs:
- [Navigator Class](https://api.flutter.dev/flutter/widgets/Navigator-class.html)
- [Navigation and Routing](https://docs.flutter.dev/development/ui/navigation)

### 🔥 Major Tasks:
- [ ] ✅ Create a 3-screen app using `Navigator.push` and named routes
- [ ] ✅ Handle data passing between screens and return on pop

---

## ✅ Stage 2: State Management  
**⏳ Timeframe:** 4–5 Days  
**🎯 Goal:** Manage app-wide state using Provider and Riverpod

### 🔹 Mini Tasks:
- [ ] Install and configure `provider` package 🔥
- [ ] Create `ChangeNotifier` for counter & theme toggle 🔥
- [ ] Update widgets using `notifyListeners()`
- [ ] Switch to `flutter_riverpod` and refactor logic 🔥
- [ ] (Optional) Use `Bloc` pattern for separation of concerns

### 📺 YouTube:
- [Provider Tutorial](https://youtu.be/d_m5csmrf7I)
- [Riverpod Crash Course](https://youtu.be/Llkj5qf9HYA)

### 🌐 Docs:
- [Provider](https://pub.dev/packages/provider)
- [Riverpod](https://riverpod.dev)

### 🔥 Major Tasks:
- [ ] ✅ Build a global theme toggler using Provider
- [ ] ✅ Switch to Riverpod and refactor the same logic

---

## ✅ Stage 3: API Integration  
**⏳ Timeframe:** 3–4 Days  
**🎯 Goal:** Fetch and display data from a REST API

### 🔹 Mini Tasks:
- [ ] Install and use `http` or `dio` package 🔥
- [ ] Fetch data from a public API like `newsapi.org` 🔥
- [ ] Convert JSON to Dart models using `json_serializable`
- [ ] Display data in a `ListView`
- [ ] Show loader using `FutureBuilder` 🔥

### 📺 YouTube:
- [Fetching APIs](https://youtu.be/x0uinJvhNxI)
- [JSON Parsing](https://youtu.be/BmIQmA8z8T4)

### 🌐 Docs:
- [http](https://pub.dev/packages/http)
- [Dio](https://pub.dev/packages/dio)

### 🔥 Major Tasks:
- [ ] ✅ Fetch and parse data from a public REST API
- [ ] ✅ Display the data with proper error/loading UI

---

## ✅ Stage 4: Firebase Authentication  
**⏳ Timeframe:** 4–5 Days  
**🎯 Goal:** Add login system using Firebase

### 🔹 Mini Tasks:
- [ ] Set up Firebase project and connect to app 🔥
- [ ] Install `firebase_core` & `firebase_auth` packages
- [ ] Implement email/password login 🔥
- [ ] Add Google Sign-In with `google_sign_in`
- [ ] Use `StreamBuilder` for login state
- [ ] Redirect to dashboard when logged in 🔥
- [ ] Protect pages using auth guards

### 📺 YouTube:
- [Firebase Auth Full App](https://youtu.be/1gDhl4leEzA)
- [Google Sign-In](https://youtu.be/kKndA6u4kT8)

### 🌐 Docs:
- [Firebase Auth](https://firebase.flutter.dev/docs/auth/overview/)
- [Google Sign-In](https://pub.dev/packages/google_sign_in)

### 🔥 Major Tasks:
- [ ] ✅ Build login + signup flows with Firebase Email/Password Auth
- [ ] ✅ Implement Google Sign-In and protect routes based on auth

---

## ✅ Stage 5: Local Storage  
**⏳ Timeframe:** 3–4 Days  
**🎯 Goal:** Store and retrieve local data using SharedPreferences & Hive

### 🔹 Mini Tasks:
- [ ] Save app state using `shared_preferences` 🔥
- [ ] Install `hive`, `hive_flutter`, and setup adapters
- [ ] Create CRUD Todo app with Hive 🔥
- [ ] Store login token/theme setting persistently

### 📺 YouTube:
- [Shared Preferences](https://youtu.be/5j12u6zlT6k)
- [Hive Local DB](https://youtu.be/zHGgP2U3_4E)

### 🌐 Docs:
- [Shared Preferences](https://pub.dev/packages/shared_preferences)
- [Hive Docs](https://docs.hivedb.dev/)

### 🔥 Major Tasks:
- [ ] ✅ Build a Todo app using Hive with full CRUD
- [ ] ✅ Persist user settings (e.g. theme or auth token)

---

## ✅ Stage 6: Push Notifications  
**⏳ Timeframe:** 3–4 Days  
**🎯 Goal:** Setup Firebase Cloud Messaging for real-time engagement

### 🔹 Mini Tasks:
- [ ] Add FCM to Flutter project 🔥
- [ ] Handle background and foreground messages
- [ ] Use `firebase_messaging` to navigate on notification tap 🔥
- [ ] Send test notifications via Firebase Console

### 📺 YouTube:
- [FCM Setup](https://youtu.be/TpLzSRTPvS0)
- [Notifications Guide](https://youtu.be/2t3D8eH3VVA)

### 🌐 Docs:
- [Firebase Messaging](https://firebase.flutter.dev/docs/messaging/overview/)

### 🔥 Major Tasks:
- [ ] ✅ Configure and receive FCM notifications
- [ ] ✅ Navigate to screens from tapped notifications

---

## ✅ Stage 7: Clean Architecture  
**⏳ Timeframe:** 2 Days  
**🎯 Goal:** Organize code in scalable folder structure

### 🔹 Mini Tasks:
- [ ] Create folders: `screens`, `widgets`, `models`, `services`, etc. 🔥
- [ ] Avoid logic in `main.dart`
- [ ] Modularize reusable components 🔥
- [ ] Use services/providers for business logic

### 📺 YouTube:
- [Folder Structure Guide](https://youtu.be/GmNMbxGvTqI)
- [Clean Architecture](https://youtu.be/MkFjtCov62g)

### 🌐 Docs:
- [Architecture Guide](https://docs.flutter.dev/development/data-and-backend/architecture)

### 🔥 Major Tasks:
- [ ] ✅ Refactor any existing app to clean modular structure
- [ ] ✅ Separate business logic into services or providers

---

## ✅ Stage 8: Responsive UI & Animations  
**⏳ Timeframe:** 3 Days  
**🎯 Goal:** Design adaptive and engaging UI

### 🔹 Mini Tasks:
- [ ] Use `MediaQuery`, `LayoutBuilder` for responsiveness 🔥
- [ ] Add `flutter_screenutil` or `responsive_framework`
- [ ] Add `Hero`, `Fade`, `Lottie` animations 🔥
- [ ] Build swipeable onboarding flow with animation

### 📺 YouTube:
- [Responsive UI](https://youtu.be/euCqAq6BRa4)
- [Animations Tutorial](https://youtu.be/7AuK4zO7-0Y)

### 🌐 Docs:
- [Animations](https://docs.flutter.dev/ui/animations)
- [Responsive Layout](https://docs.flutter.dev/ui/layout/responsive)

### 🔥 Major Tasks:
- [ ] ✅ Build a fully responsive layout (tablet + mobile)
- [ ] ✅ Add onboarding animations using Hero + Lottie

---

## ✅ Stage 9: Testing  
**⏳ Timeframe:** 4 Days  
**🎯 Goal:** Add unit, widget, and integration testing

### 🔹 Mini Tasks:
- [ ] Test pure Dart function with `test` 🔥
- [ ] Write widget test using `flutter_test` for UI logic 🔥
- [ ] Setup `integration_test` package
- [ ] Automate login + dashboard flow 🔥

### 📺 YouTube:
- [Flutter Testing](https://youtu.be/J7s5GvZBg2E)
- [Integration Testing](https://youtu.be/UfqsuzC2eZM)

### 🌐 Docs:
- [Testing Flutter](https://docs.flutter.dev/testing)

### 🔥 Major Tasks:
- [ ] ✅ Build complete test coverage (unit, widget, integration)
- [ ] ✅ Run and debug all tests using `flutter test` and `flutter drive`



---

# 🎓 Capstone Projects

## 🧠 Capstone Project 1: Smart Task Manager App

**🛠 Description:**  
A productivity app that includes authentication, state management, offline storage, notifications, and animations.

### 🔹 Features:
- [ ] User Signup/Login with Firebase 🔥  
- [ ] Create/update/delete tasks using Hive 🔥  
- [ ] Toggle between light/dark themes  
- [ ] Add reminders with FCM notifications  
- [ ] Filter tasks by date/category  
- [ ] Responsive design for mobile/tablets  
- [ ] Animated onboarding screen  
- [ ] Full test coverage (unit + widget + integration) 🔥

### 🧱 Tech Stack:
Firebase Auth, Hive, Riverpod, Firebase Messaging, flutter_screenutil, Clean Architecture

### 📺 Tutorials:
- [Task App with Firebase (YouTube)](https://youtu.be/1gDhl4leEzA)
- [Hive Todo App (YouTube)](https://youtu.be/zHGgP2U3_4E)

### 🔥 Major Capstone Goals:
- [ ] Build a fully functional productivity app  
- [ ] Apply all major Flutter concepts  
- [ ] Publish to GitHub or Google Play (optional)

---

## 🛍️ Capstone Project 2: Flutter E-Commerce Store

**🛠 Description:**  
An online shopping app that showcases authentication, product APIs, local cart, and animations.

### 🔹 Features:
- [ ] User login/registration with Firebase Auth 🔥  
- [ ] Product list from API (e.g., fakestoreapi) 🔥  
- [ ] Add to cart + quantity adjust  
- [ ] Save cart locally with Hive  
- [ ] Checkout screen and order confirmation  
- [ ] Push notifications for orders  
- [ ] Responsive and animated UI  
- [ ] Optional admin panel

### 🧱 Tech Stack:
Firebase (Auth + Messaging), Hive, REST API, Riverpod, flutter_screenutil, Modular architecture

### 📺 Tutorials:
- [Flutter E-Commerce Full App](https://youtu.be/JkBp-JpvvTo)
- [Firebase + REST API](https://youtu.be/QwkUu4K9NLc)

### 🔥 Major Capstone Goals:
- [ ] End-to-end e-commerce flow  
- [ ] Integrate backend + frontend  
- [ ] Responsive + tested + animated UX
