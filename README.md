🎬 Movie Search Web Application
📖 Overview
This is a React.js based movie search application that allows users to search for movies and view their details. It utilizes the OMDB API to fetch movie data and displays it in a clean and responsive UI.

🚀 Features
🔍 Search Movies: Search movies by title using the OMDB API.

🖼️ Grid Display: Shows movies in a responsive card grid layout.

🎞️ Movie Details Modal: View extended information (plot, genre, ratings, etc.) in a modal popup.

⚠️ Error Handling:

“No Data Found” message if no matches.

Handles API errors gracefully.

🌐 API Integration: Built using Axios for API requests.

📸 Screenshots
🏠 Homepage

Grid layout of popular or searched movies

🔑 Getting an OMDB API Key
Go to OMDB API Website.

Click on the "API Key" tab in the navbar.

Choose the free account, fill in your email and other details.

You will receive your API key via email.

🛠️ Installation
📥 Step-by-Step
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/iamsonukj/Movie-Search-Application.git
cd Movie-Search-Application
Install Dependencies:

bash
Copy
Edit
npm install
Add Your OMDB API Key:

Create a .env file in the root directory:

ini
Copy
Edit
REACT_APP_OMDB_API_KEY=your_api_key_here
Run the Application:

bash
Copy
Edit
npm start
Open your browser and visit:
👉 http://localhost:3000

💡 Usage
🔎 Search: Type a movie title and hit Enter to search.

🧾 Details: Click on a movie to open a modal with detailed info.

📦 Tech Stack
Technology	Purpose
React.js	Frontend UI Framework
Axios	HTTP Requests to OMDB API
Tailwind CSS	Styling & Responsive Layout
Redux	State Management (if used)
OMDB API	Movie data source
