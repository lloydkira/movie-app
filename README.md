**Movie Finder** 🎥

Find your next favorite movie with Movie Finder! This web application allows users to effortlessly search for movies, browse trending titles, and get personalized results based on their search queries.
Key Features 🌟
- Search Movies: Enter a movie title to instantly fetch results from The Movie Database (TMDB) API.
- Trending Movies: Check out the currently popular movies, displayed with images and rankings.
- Debounced Search Input: Prevents excessive API requests by waiting for users to finish typing.
- Error Handling: Displays user-friendly error messages for any issues while fetching data.
- Loader Animation: A sleek spinner shows while the app fetches your movie data.

**Technologies Used** 🚀
- React: Modern JavaScript framework for building the UI.
- React-Use: Used for implementing debouncing.
- Appwrite: Backend service for storing trending movies and managing search counts.
- TMDB API: Fetch movie details and trending data.
- JavaScript & ES6: For creating reusable and clean logic.

**How It Works** ⚙️
- Enter a movie title in the Search bar.
- The app sends a search request to the TMDB API, displaying relevant movie results in seconds.
- Trending movies are fetched from Appwrite and displayed in a separate section.
- A debounced input ensures minimal API calls for an optimized user experience.

**Installation** 🛠️
Clone the repository, navigate to the project directory, and install the dependencies. Set up your .env file with your TMDB API key, and then start the development server to view the app locally.
Screenshots 📸
Include screenshots of your app, such as the search interface and the trending movies section, to showcase its appearance and functionality.
Future Enhancements 🚀
- Add detailed movie pages with more information about each title.
- Implement user accounts for saving watchlists.
- Add genre filters for better browsing options.

**License** 📜
This project is open-source and available under the MIT License.

Happy movie hunting 🎬✨
