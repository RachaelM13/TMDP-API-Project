# TMDB Yearly Movie Data Exporter

This project is an application that leverages the [TMDB API](https://www.themoviedb.org/documentation/api) to retrieve movie data for a specified year and generate a CSV file with detailed information about the top 10 movies from that year.

## Features

- **Retrieve Top 10 Movies:** Fetches the top 10 movies for a given year using TMDB's database.
- **CSV File Generation:** Saves the movie data to a `.csv` file with three sorting options:
  - **By Votes:** Movies are sorted in descending order based on the number of votes.
  - **By Name (Full):** Movies are sorted alphabetically by their full titles, including prefixes like "A" or "The."
  - **By Name (Ignoring Prefix):** Movies are sorted alphabetically while ignoring prefixes like "A" or "The" at the beginning of titles.

## Output Format

The generated `.csv` file will include three separate sections, each representing one of the sorting methods. This makes it easy to analyze the data from different perspectives.

## How to Use

1. Clone the repository.
2. Set up your TMDB API key in the application's configuration.
3. Run the application and provide a year as input.
4. The app will generate a `.csv` file containing the sorted lists.

## License

This project is licensed under the [MIT License](LICENSE).

---

Discover the top movies from any year and export them effortlessly! 🎥
