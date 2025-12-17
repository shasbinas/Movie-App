# 🎬 Movie Discovery App

A modern, responsive movie discovery application built with **React**, **Tailwind CSS**, and **Appwrite**. Browse trending movies, search for your favorites, and explore details with a stunning user interface.

![Movie App Hero](public/hero.png)

## ✨ Features

- **🔎 Real-time Search**: Instant movie search with debouncing for optimized API calls.
- **🔥 Trending Movies**: See what's popular right now, powered by Appwrite backend metrics.
- **📱 Fully Responsive**: A seamless experience across desktop, tablet, and mobile devices.
- **🎨 Modern UI**: Beautiful dark-themed interface with glassmorphism effects and smooth animations.
- **⚡ High Performance**: Built with Vite for lightning-fast development and production builds.

## 🛠️ Tech Stack

- **Frontend**: [React](https://reactjs.org/) (Vite)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Backend/Database**: [Appwrite](https://appwrite.io/) (for tracking trending metrics)
- **API**: [TMDB (The Movie Database)](https://www.themoviedb.org/)

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/movie-app.git
   cd movie-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Environment Variables**
   Create a `.env` file in the root directory and add your API keys:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key_here
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

4. **Run the Development Server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

## 📁 Project Structure

```
├── src/
│   ├── components/      # Reusable UI components (Search, MovieCard, etc.)
│   ├── assets/          # Static assets (images, icons)
│   ├── appwrite.js      # Appwrite configuration and API logic
│   ├── App.jsx          # Main application component
│   └── main.jsx         # Entry point
├── public/              # Public assets
└── ...config files
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
