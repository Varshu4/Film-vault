# Film-vault
**Film-Vault** is a React-based web application designed to help users explore movies and manage their personalized watchlists. The app integrates with the TMDB API to fetch the latest movies, allowing users to discover trending content effortlessly.

## Features

- **Navigation**: The site features a responsive navbar with options for Movies and Watchlist, built using React Router for seamless navigation.
  
- **Movies Tab**: 
  - Contains a **Banner** and a **Trending Movies** section.
  - Utilizes reusable **MovieCard** components within a React Fragment.
  - Supports pagination for browsing through multiple pages of movies.
  - Icons are sourced from Font Awesome.

- **Watchlist Tab**:
  - Displays movies in a table format with columns for Movie Name, Rating, Popularity, Genre, and a delete option.
  - Includes genre-based filtering and sorting by rating in ascending or descending order.
  
- **Search**: Users can search for movies by name.

- **Watchlist Management**:
  - Add movies to the watchlist using a button on each MovieCard.
  - If a movie is already on the watchlist, it is indicated with a cross button.
  - Persistent storage of the watchlist using **local storage** ensures the watchlist remains intact even after refreshing the page.
  - When a movie is deleted from the watchlist, it is also removed from local storage.

## Setup

1. Clone the repository.
2. Run `npm install` to install dependencies in integrated terminal.
3. Start the development server with `npm run dev`.

## Future Enhancements

- Implement user authentication for personalized watchlists.
- Add support for more advanced search filters (e.g., by release date, cast).

---
