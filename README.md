# Collecting-data-Assignment-4

# Corpus Description

This corpus covers book information extracted from the Goodreads website, primarily covering book titles, authors, average ratings, and the number of popular Kindle notes. The data is derived from two primary sources, the list of "Best Books Ever" and the New York Times' 100 Notable Books of 2023 on the Goodreads platform.

## Target Audience and Purpose

The target audience includes researchers and online readers. This corpus is applicable for literary trend analysis, cross-genre analysis, and assisting readers in selecting books of interest.

By conducting a comparative analysis between the list of "Best Books Ever" and the New York Times' 100 Notable Books of 2023, exploration in the following areas is facilitated:

- **Emerging Trends:** Analyzing frequently occurring genres or themes in the lists helps identify emerging trends in the literary domain, providing insights into the sustained popularity of these genres or types.

- **Author Influence:** Identifying authors with multiple books in the lists highlights influential writers and their contributions to the literary landscape, aiding in understanding the significance of these authors in the current literary environment.

- **Genre Preferences:** Subdividing the lists by genre analyzes which genres dominate, assisting publishers and authors in understanding which types of books may have a lasting impact.

- **Cross-Genre Analysis:** Exploring the presence of cross-genre books in the lists indicates an increasing interest in blended or innovative stories, reflecting a trend toward interdisciplinary literary creations.

## Text Selection Criteria

Data is primarily sourced from two Goodreads lists, the list of "Best Books Ever" and the New York Times' 100 Notable Books of 2023 on the Goodreads platform. For each list, the top 20 books were selected based on title, author, avg rating, and the first five genre labels.

## Data Collection Process

Data collection involved web scraping of pages on the Goodreads website. The Python programming language, spaCy and BeautifulSoup libraries, was employed to parse web pages and extract the required information to collect The itle, author, rating, and the first five genre labels of each book in the top 20 of the two list. The corpus was saved as a data directory containing corpus files in the text format and a single CSV file with all corpus data.

## Cleaning and Preprocessing Steps

Preprocessing steps encompassed cleaning and organizing the text extracted from web pages to ensure data consistency and availability.

## Annotations and Tools

Data collection utilized the Python programming language, spaCy and BeautifulSoup libraries the Requests library for web page requests and the BeautifulSoup library for HTML parsing. Corpus Description and comments were added to relevant code sections to enhance code readability.

## File Format in the Corpus

A data directory containing corpus files in the text format and a single CSV file with all corpus data and annotations, including the following columns:

- Title
- Author
- Avg Rating
- Genre
- Tokens
- Lemmas
- Parts of Speech
- Source
- Rank

## Quality Check

Data underwent an initial quality check to ensure consistency with the content on the source web pages.

## Additional Considerations

Due to the limited sample size, for specific analytical purposes, it is recommended to integrate other data sources and information for a more comprehensive perspective.
