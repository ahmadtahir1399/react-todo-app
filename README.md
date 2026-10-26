<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,55:1c1d20,100:0c63e7&height=170&section=header&text=React%20Todo%20App&fontSize=48&fontColor=fcfaf8&fontAlignY=38&desc=Animated%20todos%20with%20Context%20%2B%20Framer%20Motion&descAlignY=60&descSize=16" width="100%" alt="React Todo App" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
</p>

## ✨ About

A todo app with smooth animations. Global state lives in the **React Context API**, todos are saved to **localStorage** so they survive a refresh, and **Framer Motion** animates items as they're added, completed and removed.

## 🔋 Features

- ➕ Add, ✏️ edit, ✅ complete and 🗑️ delete todos
- 💾 Persists to `localStorage` automatically
- 🌐 App-wide state with `createContext` / `useContext`
- 🎞️ Animated list items and transitions with Framer Motion
- 🆔 Unique IDs with `uuid`

## 🛠️ Tech stack

React 18 · Vite · Context API · Framer Motion · Tailwind CSS · clsx + tailwind-merge

## 🚀 Getting started

The app lives in the `ToDo App` folder:

```bash
git clone https://github.com/ahmadtahir1399/react-todo-app.git
cd "react-todo-app/ToDo App"
npm install
npm run dev
```

## 📁 Project structure

```
ToDo App/src/
  Context/      TodoContext (provider + useTodo hook)
  components/   TodoForm, TodoItem, ui/
  App.jsx       localStorage sync + layout
```

## 👤 Author

**Muhammad Ahmad Tahir** · [Portfolio](https://ahmadverse.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/ahmad-ai-fullstack-engineer/) · [GitHub](https://github.com/ahmadtahir1399)
