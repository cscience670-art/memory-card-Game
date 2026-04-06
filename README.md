# 🧠 Memory Card Game (Expo React Native)

Welcome to the **Memory Card Game**! This project is a hands-on learning experience designed for first-year computer science students. In an era where AI can write code in seconds, the true value of a programmer lies in **logical thinking** and **problem-solving**. This project is built to sharpen those exact skills.

---

## 🎯 Purpose
The goal of this project isn't just to build an app—it's to understand the "why" behind the "how." By exploring this codebase, you will focus on:
* **Logical Thinking:** Managing game states and win conditions.
* **Problem Decomposition:** Breaking a complex game into small, manageable components.
* **React Native Mastery:** Learning the nuances of mobile UI and state management.
* **Modern Routing:** Using Expo Router for seamless navigation.

---

## 📱 Tech Stack
* **Framework:** [React Native](https://reactnative.dev/) with [Expo](https://expo.dev/)
* **Language:** [TypeScript](https://www.typescriptlang.org/) (for type safety and better DX)
* **Routing:** Expo Router (File-based navigation)
* **Styling:** React Native StyleSheet

---

## 🎮 How the Game Works
1.  **The Grid:** Cards are shuffled and displayed face down.
2.  **The Flip:** The player selects two cards to flip.
3.  **The Match:** * If the cards match, they stay visible and are marked as "found."
    * If they don't match, they flip back after a short delay (e.g., 1000ms).
4.  **The Win:** The game ends when all pairs are successfully matched.

---

## 📂 Project Structure
```text
app/
├── _layout.tsx    # App entry point & navigation structure
└── index.tsx      # Main game screen (UI + Game Logic)
assets/            # Images, icons, and fonts
components/        # Reusable UI components (Card, Timer, etc.)
```

---

## 🚀 Getting Started

### 1️⃣ Install Dependencies
Clone the repository and install the necessary packages:
```bash
npm install
```

### 2️⃣ Start the Project
Launch the Expo development server:
```bash
npx expo start
```

### 3️⃣ Run on Your Device
* **Physical Device:** Open the **Expo Go** app (Android/iOS) and scan the QR code.
* **Android:** Press `a` to open the Android Emulator.
* **iOS:** Press `i` to open the iOS Simulator.

---

## ✨ Features
* 🎨 **Clean UI:** Simple, distraction-free design.
* 🔄 **Card Animations:** Smooth flip transitions for a polished feel.
* 🧠 **Smart Logic:** Robust state handling for matching and shuffling.
* ⏱️ **Timer System:** Track how fast you can clear the board.
* 🎮 **Difficulty Levels:** Adjustable grid sizes for different challenges.
* 📱 **Cross-Platform:** Works seamlessly on both Android and iOS.

---

## 📚 Learning Outcomes
By studying this project, you will master:
* **State Management:** Using `useState` and `useEffect` to control game flow.
* **Component Architecture:** Keeping code "DRY" (Don't Repeat Yourself).
* **Timing Logic:** Handling asynchronous actions like `setTimeout` for card flips.
* **TypeScript Basics:** Defining interfaces for game objects and props.

---

## 👨‍💻 Author
**Sadek Amine**

💡 Future Improvements
Score system 🏆
Sound effects 🔊
Leaderboard system 📊
Better animations 🎬
