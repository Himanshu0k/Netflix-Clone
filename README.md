
# NETFLIX Clone

Netflix Clone is a full-stack web application built with MERN stack, replicating the core features of Netflix. It includes movie and TV show browsing, user authentication with JWT, and a fully responsive Netflix-style UI. Users can watch trailers, view personalized recommendations, and explore content via APIs. The backend, powered by Node.js and Express, manages authentication and data storage with MongoDB. The app delivers a seamless streaming-like experience with React, dynamic routing, and an intuitive user interface.


## Features

🎬 User Features
- ✅ Movie & TV Show Browsing – Users can explore a wide range of movies and TV shows.
- ✅ Search Functionality – Search movies and TV shows by title, genre, or category.
- ✅ Movie & TV Show Details – View detailed information like synopsis, rating, genre, cast, and release date.
- ✅ Watch Trailers – Watch official trailers for movies and TV shows.
- ✅ Suggested Movies & TV Shows – Get personalized recommendations based on what you watch.
- ✅ Category-Based Filtering – Browse content by categories like Popular, Trending, Top Rated, and Genre.
- ✅ Pagination & Infinite Scroll – Load more movies seamlessly for a smooth browsing experience.

🔐 Authentication & User Management
- ✅ User Registration & Login – Secure authentication system using JWT.
- ✅ Google/Facebook OAuth (Optional) – Sign in with Google or Facebook.
- ✅ Password Hashing – Secure user passwords using bcrypt.
- ✅ User Profiles – Create multiple profiles under a single account (like Netflix).
- ✅ Logout Functionality – Securely log out from the application.

📺 Netflix-Like UI/UX
- ✅ Responsive Design – Fully responsive UI that works across all devices.
- ✅ Dark Mode – Netflix-like dark theme for a cinematic experience.
- ✅ Slick Carousels – Smooth scrolling movie carousels using Swiper.js or Slick.js.
- ✅ Hover Previews – Show quick previews when hovering over movie cards.

🎥 Media & Streaming Features
- ✅ Play Trailers – Click on a movie card to watch the trailer.
- ✅ Auto-Play Next Trailer – Continuously play trailers while browsing.

🔍 Advanced Search & Filtering
- ✅ Genre Filtering – Find movies & TV shows by specific genres.
- ✅ Sort by Popularity, Release Date, Ratings – Sort content based on different criteria.

🔄 Content Management & API Integration
- ✅ Dynamic Movie Data – Fetch real-time movie & TV show data using The Movie Database (TMDB) API.
- ✅ Trending & Popular Section – Display trending, upcoming, and top-rated content.
- ✅ Cast & Crew Information – Show actors, directors, and crew members.

🛡️ Security & Performance
- ✅ JWT Authentication – Secure authentication system for user login/signup.
- ✅ Data Validation – Validate user inputs to prevent errors and malicious data.
- ✅ Secure API Calls – Use HTTPS and token-based authentication for API requests.
- ✅ Optimized Loading – Lazy loading for images and components to improve performance.

📦 Backend & Database Features
- ✅ Node.js & Express Backend – Handles authentication, user data, and API requests.
- ✅ MongoDB Database – Stores user information, favorites, and watch history.
- ✅ RESTful API Development – Backend API endpoints for user authentication and movie data retrieval.


## Tech Stack

Frontend (Client-Side) 🖥️
- React.js – Frontend framework for building the UI

- React Router – Handles client-side routing

- Tailwind CSS / Material-UI / Styled Components – For styling the Netflix-like UI

- Axios – For making API requests

Backend (Server-Side) 🛠️
- Node.js – Runtime environment for executing JavaScript on the server

- Express.js – Web framework to handle API requests and authentication

- JWT (JSON Web Token) – Authentication and user session management

- Bcrypt.js – For password hashing and security

Database 🗄️
- MongoDB – NoSQL database to store user data, watchlists, and favorites

- Mongoose – ODM (Object-Document Mapping) for interacting with MongoDB

External APIs & Services 🌐
- TMDB API – Fetches movie and TV show data

Development & Deployment 🚀
- Git & GitHub – Version control and collaboration

- dotenv – To manage environment variables securely


## Installation

Prerequisites
Before running the project, ensure you have:
- ✅ Node.js installed → Download
- ✅ MongoDB running (local or Atlas)
- ✅ A TMDB API Key → Get it here

Clone the Repository
- git clone https://github.com/yourusername/Netflix-Clone.git
- cd Netflix-Clone

Environment Variables
- MONGO_URI = your_mongodb_connection_string
- PORT = your_port_number
- JWT_SECRET = your_secret_key
- TMDB_API_KEY = your_tmdb_api_key

Backend
- cd server
- npm install   
- npm run dev 

Frontend
- cd ../client
- npm install
- npm run dev


## Usage

1️⃣ Open the application

- Visit http://localhost:your_port in your browser after running the app.

2️⃣ Sign Up / Login

- Create a new account or log in with your credentials.

3️⃣ Browse Movies & TV Shows

- Explore different categories like Trending, Top Rated, Popular, etc.

- Use the search bar to find specific movies or shows.

- Click on a movie card to view detailed information.

4️⃣ Watch Trailers

- Click on the "Play Trailer" button to watch trailers before selecting a movie.

5️⃣ View Recommendations

- Scroll down on a movie page to see similar and recommended content.

6️⃣ Logout

- Click on the profile/logout button to securely sign out.

🔹 Notes:
- If the API does not fetch movies, ensure your TMDB API Key is correctly set in .env.

- If the backend is not running, restart it using npm run dev in the server folder.

- You can modify the UI components (React) or backend routes as needed.
