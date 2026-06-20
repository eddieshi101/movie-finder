# 🎬 MovieFinder

A modern, highly responsive React web application that allows users to discover popular movies, search a global database via real-time asynchronous API integration, and curate a persistent list of personal favorites.

Built on top of **React 19** and bundled with **Vite 8**, this project delivers exceptional performance, instantaneous hot-module replacement (HMR), and lightning-fast build speeds.

---

## ✨ Features

- **🔥 Real-Time Discoverability:** Dynamically fetches and showcases currently popular movies straight from The Movie Database (TMDB) REST API on initial page mount.
- **🔍 Intelligent Search Engine:** Debounced asynchronous lookup utility that queries the global TMDB database with URL-safe query sanitization.
- **❤️ Global Contextual Favorites Framework:** Uses a centralized state wrapper layer implementing React Context to instantly sync favorited items across decoupled views without prop drilling.
- **💾 Persistent Browser Storage System:** Leverages the client-side `localStorage` subsystem to maintain your custom favorites list seamlessly across session reloads and browser closures.
- **🛡️ Data Integrity Guards:** Built-in fallback architectures (optional chaining operators and default content triggers) ensuring full stability against sparse or incomplete API objects.

---

## 🛠️ Tech Stack & Architecture

- **Core Framework:** React 19 (Component-driven structure)
- **Routing Engine:** React Router DOM v7 (Declarative client-side SPAs routing architecture)
- **Build Tooling & Server:** Vite v8 + Rolldown (Next-generation lightning bundling)
- **Linter System:** ESLint v10 (Strict semantic and syntax validation standard)
- **External Integration:** The Movie Database (TMDB) v3 REST API

---

## 🚀 Getting Started

Follow these steps to configure your workspace and run the movie dashboard application locally on your machine.

### 📋 Prerequisites

Ensure you have **Node.js** installed on your system:
- [Node.js (v18.0.0 or higher recommended)](https://nodejs.org/)

### 🔧 Installation Steps

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/eddieshi101/movie-finder.git](https://github.com/eddieshi101/movie-finder.git)
   cd movie-finder/frontend
