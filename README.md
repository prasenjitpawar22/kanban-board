# Kanban Board Project

Live project link - https://board-bice-psi.vercel.app

A simple, responsive Kanban board built using **Next.js**, **Tailwind CSS**, and TypeScript. This project demonstrates basic drag-and-drop functionality for task management, showcasing reusable components and clean project structure.

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn

### Installation

```bash
git clone https://github.com/yourusername/kanban-board.git
cd kanban-board
npm install
# or
yarn install
```


# 🏗️ Architecture & Approach
App Directory: Uses Next.js 13+ app/ directory structure for routing.

Components: Modular and reusable UI elements located in /components.

State Management: Local component state to track board lists and tasks.

Styling: Tailwind CSS for utility-first, responsive UI design.

Type Safety: TypeScript used throughout to ensure cleaner, safer code.




# Self-Evaluation

## 📝 Half-Page Summary

This is a lightweight Kanban board project developed using Next.js, Tailwind CSS, and TypeScript. It demonstrates clean UI implementation with modular components and responsive design. The goal was to build a basic task board with support for expanding into drag-and-drop interactions and a dynamic data layer.

## 🧠 Self-Criticism

- Board/task data is stored locally instead of using any external state manager or API.
- The folder structure is simple but could benefit from clearly separating logic vs. UI.
- Form/Model validation not implemented.

## 🔧 Improvements If I Had More Time

- Add persistent storage (e.g. Supabase or any other database).
- Improve UI feedback, such as loading states or animations.
- Add tests (unit/component) using a framework like Vitest or Jest.

## 📊 Technology Rating

- **React / Next.js**: 9/10  
- **Tailwind CSS**: 9/10  
- **TypeScript**: 8/10  
