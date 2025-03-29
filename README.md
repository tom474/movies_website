# Movies Website

A modern and responsive web application for discovering movies. Built with React, Tailwind CSS, and powered by Appwrite, this platform allows users to explore a rich collection of films with an intuitive and visually appealing interface. Whether you're looking for trending titles or searching for a specific movie, this website delivers a smooth and enjoyable browsing experience.

## Tech Stack

- React.js
- Tailwind CSS
- Appwrite

## Features

- **Browse All Movies**: Explore a wide range of movies available on the platform.
- **Search Movies**: Easily search for specific movies using a search function.
- **Trending Movies Algorithm**: Displays trending movies based on a dynamic algorithm.
- **Modern UI/UX**: A sleek and user-friendly interface designed for a great experience.
- **Responsiveness**: Fully responsive design that works seamlessly across devices.

## Quick Start

> Follow these steps to set up the project locally on your machine.

Clone the repository

```bash
git clone https://github.com/tom474/movies_website.git
```

Navigate to the project directory

```bash
cd movies_website
```

Create `.env.local` file in the root folder and set up environment variables

```
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

Install dependencies

```bash
npm install
```

Start the application
```bash
npm run dev
```