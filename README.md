# Movie Listing Website

This is a **responsive movie listing website** built with **React.js**, demonstrating modern frontend development practices, including:

- React Hooks
- Context API for global state management
- API integration using **OMDb API**
- Responsive design with mobile, tablet, and desktop breakpoints
- Search functionality with **debouncing** and **type-ahead suggestions**
- Infinite scroll for seamless movie browsing
- **React Router** for multi-page navigation
- **Material-UI** for UI components and layout

---

## 🔗 Live Demo (Optional)

[Hosted Link (if deployed)](https://your-deployment-url.com)

---

## 📚 Features

### 1. Movie Listing Page
- Displays a grid of movies fetched from the **OMDb API**.
- Infinite scroll to automatically load more movies as the user scrolls.
- Search bar with:
    - **Debounced search (with lodash debounce)** to avoid excessive API calls.
    - **Type-ahead suggestions** that show movie titles matching the search query.
- Responsive grid layout for different devices (mobile, tablet, desktop).

### 2. Movie Details Page
- Displays **detailed information** about the selected movie.
- Includes back navigation to the listing page.
- Fully responsive design.

### 3. Search Functionality
- Implements search with:
    - Debouncing to minimize API calls.
    - Dynamic suggestion dropdown.
    - Clicking a suggestion loads the movie details page.

### 4. Error Handling & Loading States
- API errors are gracefully handled and shown to the user.
- Loading indicators appear during API fetches.

---

## 🛠️ Tech Stack

| Technology        | Description                                                                                   |
|-------------------|-----------------------------------------------------------------------------------------------|
| React.js           | Core library for UI development.                                                             |
| React Router       | For page navigation and routing.                                                             |
| Material-UI        | For UI components like Cards, Typography, and Grid.                                          |
| Context API        | For global state management (like search query state).                                       |
| OMDb API           | Movie data source.                                                                           |
| Lodash             | For implementing search **debounce**.                                                         |
| CSS/SCSS           | For custom styles.                                                                           |

---

## 📡 API Details

Base URL: [https://www.omdbapi.com/](https://www.omdbapi.com/)  
API Key: `b9bd48a6` (Use your own key if needed)

### Example Endpoints:
- Search movies:  
    ```
    https://www.omdbapi.com/?apikey=b9bd48a6&s=marvel
    ```
- Pagination (page 2 example):  
    ```
    https://www.omdbapi.com/?apikey=b9bd48a6&s=marvel&page=2
    ```
- Get movie details:  
    ```
    https://www.omdbapi.com/?apikey=b9bd48a6&i=tt3896198
    ```

---

## 🏗️ Project Structure

