
<div align="center">
  <br />
    <a href="https://youtu.be/YOUR_DEMO_LINK" target="_blank">
      <img src="assets/readme/hero.png" alt="Project Banner">
    </a>
  <br />
  <div>
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="expo" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

  <h3 align="center">🏡 Real Scout – Real Estate App</h3>

   <div align="center">
     A modern cross-platform real estate application built with React Native, designed for browsing, searching, and managing property listings with ease.
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>
1. 🤖 [Introduction](#introduction)  
2. ⚙️ [Tech Stack](#tech-stack)  
3. 🔋 [Features](#features)  
4. 🤸 [Quick Start](#quick-start)  
5. 📞 [Contacts](#contacts)
6. 🚀 [Show Your Support](#show-your-support)

---

## <a name="introduction">🤖 Introduction</a>

**Real Scout** is a full-stack real estate mobile app built using **React Native**, **Expo SDK 52**, **Appwrite**, **Tailwind CSS**, and **TypeScript**.  
It allows users to search, filter, and view property details, save favorites, and manage their profiles — all in one seamless and visually appealing interface.

---

## <a name="tech-stack">⚙️ Tech Stack</a>

- **[Expo](https://expo.dev/)** – Expo is an open-source platform for building universal native apps (Android, iOS, web) using JavaScript/TypeScript and React Native. It features file-based routing via Expo Router, fast refresh, native modules for camera/maps/notifications, over-the-air updates (EAS), and streamlined app deployment.
- **[React Native](https://reactnative.dev/)** – React Native is a framework for building mobile UIs with React. It enables component‑based, cross-platform development with declarative UI, deep native API support, and is tightly integrated with Expo for navigation and native capabilities.
- **[Appwrite](https://appwrite.io/)** – Appwrite is an open-source backend-as-a-service platform offering secure authentication (email/password, OAuth, SMS, magic links), databases, file storage with compression/encryption, real-time messaging, serverless functions, and static site hosting via Appwrite Sites—all managed through a unified console and microservices architecture.
- **[TypeScript](https://www.typescriptlang.org/)** – TypeScript is a statically-typed superset of JavaScript providing type annotations, interfaces, enums, generics, and enhanced tooling. It improves error detection, code quality, and scalability—ideal for robust, maintainable projects.
- **[NativeWind](https://www.nativewind.dev/)** - NativeWind brings Tailwind CSS to React Native and Expo, allowing you to style mobile components using utility-first classes for fast, consistent, and responsive UI design.
- **[Tailwind CSS](https://tailwindcss.com/)** – Tailwind CSS is a utility-first CSS framework enabling rapid UI design via low-level classes. In React Native/Expo, it’s commonly used with NativeWind to apply Tailwind-style utilities to mobile components.


## 🎨 UI/UX Design

The entire interface of **Real Scout – Real Estate App** was designed with a focus on delivering a seamless and engaging property-browsing experience.  
From the onboarding screens to property detail views, every element follows a clean, modern, and user-friendly design system that enhances both functionality and aesthetics.

<p align="center">
  <a href="https://www.figma.com/design/F0pys4nJsQXz42KOzI2yl9/Real-Scout---Real-Estate-App?node-id=2-2&t=PjxkudNOJCqZHm97-1" target="_blank">
    <img src="https://img.shields.io/badge/View%20Figma%20Design-blue?style=for-the-badge&logo=figma&logoColor=white" alt="Figma Link" />
  </a>
</p>

> ✨ Crafted with attention to detail to ensure a smooth user journey across Android and iOS platforms.


---

## <a name="features">🔋 Features</a>

- 🔐 **Google Authentication** – Secure login for users.  
- 🏠 **Home Page** – Shows latest and recommended properties with search and filter.  
- 🌎 **Explore Page** – Browse all property types with an intuitive UI.  
- 🏡 **Property Details Page** – View photos, pricing, and full property information.  
- 👤 **Profile Page** – Manage profile details and preferences.  
- ⚡ **Centralized Data Fetching** – Inspired by TanStack’s `useQuery` for efficient API calls.  

---

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**
```bash
git clone https://github.com/Itssanthoshhere/Real-Scout.git
cd Real-Scout
````

**Installation** 

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=
```

Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up & creating a new project on the [**Appwrite Dashboard**](https://jsm.dev/rn25-appwrite).

**Start the app**
   
```bash
 npx expo start
```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).



---

## 🙌 Special Thanks

Inspired by **JavaScript Mastery’s** tutorials, but built with my own improvements, custom UI, and bug fixes.

---

## <a name="contacts">🔗 Contacts</a>

Feel free to connect with me:

* GitHub: [Itssanthoshhere](https://github.com/Itssanthoshhere)
* LinkedIn: [Santhosh VS](https://www.linkedin.com/in/thesanthoshvs/)

---

## ⭐️ Show Your Support

If you liked this project, drop a ⭐ on the repo and share it with others!
