Movie Finder App
This is a simple React application that allows users to search for movie information using the OMDB API.

Features
Search for movies by their title.
View detailed information about the searched movie, including title, year, genre, plot, actors, director, writer, and awards.
Dynamic display of movie poster and details upon successful search.
Technologies Used
React.js
JavaScript (ES6+)
HTML5
CSS3
Getting Started
To run this application locally, follow these steps:

Clone this repository to your local machine.
bash
Copy code
git clone https://github.com/your-username/movie-finder.git
Navigate to the project directory.
bash
Copy code
cd movie-finder
Install dependencies using npm or yarn.
bash
Copy code
npm install
or

bash
Copy code
yarn install
Obtain an API key from the OMDB API website (it's free for limited use).

Create a .env file in the project root and add your OMDB API key.

plaintext
Copy code
REACT_APP_OMDB_API_KEY=your-api-key-here
Start the development server.
bash
Copy code
npm start
or

bash
Copy code
yarn start
Open your browser and navigate to http://localhost:3000 to view the application.
Usage
Enter the title of the movie you want to search for in the search bar.
Click the "Search" button to retrieve information about the movie.
If the movie is found, detailed information along with the movie poster will be displayed.
If the movie is not found, an appropriate message will be displayed.
Credits
This application was created by Atharva Pande.

License
This project is licensed under the MIT License - see the LICENSE file for details.
