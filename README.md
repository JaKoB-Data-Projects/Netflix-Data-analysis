# Netflix 1990s Action Movie Length Analysis

This mini-project analyzes the duration of action movies produced between 1990 and 1999 found in a Netflix dataset. The analysis includes:

- Filtering out non-movie genres (specifically "International TV").
- Focusing on movies released in the 1990s.
- Drawing a histogram of movie durations for this period.
- Calculating how many 1990s action movies have a duration less than 90 minutes.

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/JaKoB-Data-Projects/Netflix-Data-analysis.git
   cd Netflix-Data-analysis
   ```
2. **Install requirements:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the code:**  
   Make sure `netflix_df` is loaded with the Netflix dataset containing at least these columns: `genre`, `release_year`, `duration`.
   Then run the analysis script or notebook.

## Example Output

- **Histogram:** Distribution of movie durations in the 1990s.
- **Short action movie count:** Number of 1990s action movies with duration under 90 minutes.

## License

MIT License.# Netflix-Data-analysis
Investingating Netflix Movies
