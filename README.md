# FlashCard App 📱✨

A modern React Native & Expo mobile application designed for interactive learning, featuring dynamic views (`Home.tsx`, `index.tsx`), layouts, and smooth animations powered by Lottie.

---

## 📂 Repository Structure

```text
FlashCard1/
│
├── app/
│   ├── Home.tsx         # Main dashboard / home screen view
│   ├── _layout.tsx      # Root layout configuration and navigation wrapper
│   └── index.tsx        # Entry point route screen
│
├── assets/
│   ├── Location Lottie Animation.json  # Location animation asset
│   ├── Pay Now.json                    # Payment/Checkout animation asset
│   └── Welcome Animation.json          # Welcome screen animation asset
│
├── .vscode/             # Editor workspace settings and extensions
├── app.json             # Expo project configuration
├── package.json         # Node.js dependencies and scripts
├── tsconfig.json        # TypeScript configuration
└── eslint.config.js     # Linter rules configuration
```

## 🚀 Key Features
1. Cross-Platform Mobile UI: Built using React Native and Expo Router (app/ directory architecture) for seamless navigation.
2. Interactive Animations: Utilizes rich Lottie JSON animations (assets/) for welcoming users, location guides, and interactive components.
3. TypeScript Support: Fully typed codebase ensuring robust state management and component structure.

## 💻 Getting Started & Installation
Ensure you have Node.js and npm (or yarn) installed on your machine.

## 🖥️ Installation & Execution (Windows & Linux)
Clone the repository:

```Bash
git clone [https://github.com/dragon-udfly/FlashCard1.git](https://github.com/dragon-udfly/FlashCard1.git)
```
Navigate into the project directory:

```Bash
cd FlashCard1
```
Install dependencies:

```Bash
npm install
```
Run the development server (Expo):

```Bash
npx expo start
```
