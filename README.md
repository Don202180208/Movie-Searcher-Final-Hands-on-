---

# Movie Searcher Web App

## Overview

The Movie Searcher Web App is a simple web application that allows users to search for movies, view upcoming releases, and explore detailed information about specific movies. The app utilizes the third-party REST API from [The Movie Database (TMDb)](https://www.themoviedb.org/) to fetch movie data.

## Features

- **Displays Upcoming Movies**: The home page displays a list of upcoming movies retrieved from TMDb.

- **Search Movies by Name**: Users can search for movies based on their names. The search results are displayed on the home page.

- **Comprehensive Movie Information**: Double-clicking on a movie card reveals detailed information about the selected movie, including its overview.

- **Similar Movies**: The detailed view of a movie includes a list of similar movies. Users can click on these to explore more movies.

- **Cam Recorded Badge**: Movies with cam recording characteristics are labeled with a "Cam Recorded" badge.

- **Category Badges**: Movies display badges indicating their genres (categories), providing additional information.

- **TV Series Badge**: TV series are identified and labeled with a "TV Series" badge.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/movie-searcher-web-app.git
   ```

2. Open the `index.html` file in your preferred web browser.

3. Use the search bar to find movies or explore the upcoming releases.

## API Key

To use this app, you need to obtain an API key from [The Movie Database (TMDb)](https://www.themoviedb.org/) and replace the `apiKey` variable in the script with your own key.

```javascript
const apiKey = 'YOUR_TMDB_API_KEY';
```

## Requirements

- Web browser with JavaScript enabled.
- Internet connection for fetching movie data from TMDb.

## Technologies Used

- HTML
- CSS
- JavaScript
- Axios (for making API requests)

## Credits

- [The Movie Database (TMDb)](https://www.themoviedb.org/) for providing the movie data.

## License

This project is licensed under the [MIT License](LICENSE).

---
