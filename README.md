# Spotify-Database-Exploration-with-Query-Optimization


Spotify dataset which I used : https://www.kaggle.com/datasets/sanjanchaudhari/spotify-dataset


https://tse4.mm.bing.net/th/id/OIP.53NR756R-0CihKlw2pdtxwHaD4?cb=defcachec2&rs=1&pid=ImgDetMain&o=7&rm=3

## Overview
I have completed a comprehensive SQL project focused on analyzing a Spotify dataset containing detailed information about tracks, albums, and artists.
In this project, I worked through the entire end-to-end process — performing SQL queries of varying complexity (easy, medium, and advanced).

I also implemented query optimization techniques to improve performance and efficiency.
Through this project, I strengthened my advanced SQL skills and generated meaningful insights from the dataset, demonstrating my ability to handle real-world data analysis tasks using structured query language.

## Project Steps
### 1. Data Exploration
The dataset contains attributes such as:
- `Artist`: The performer of the track.
- `Track`: The name of the song.
- `Album`: The album to which the track belongs.
- `Album_type`: The type of album (e.g., single or album).
- Various metrics such as `danceability`, `energy`, `loudness`, `tempo`, and more.

### 2. Querying the Data
After the data is inserted(Manually or through CSV), various SQL queries can be written to explore and analyze the data. Queries were categorized into **easy**, **medium**, and **advanced** levels to help progressively develop SQL proficiency.

#### Easy Queries
- Simple data retrieval, filtering, and basic aggregations.
  
#### Medium Queries
- More complex queries involving grouping, aggregation functions, and joins.
  
#### Advanced Queries
- Nested subqueries, window functions, CTEs, and performance optimization.


### 3. Query Optimization
In advanced stages, the focus shifts to improving query performance. Some optimization strategies include:
- **Indexing**: Adding indexes on frequently queried columns.
- **Query Execution Plan**: Using `EXPLAIN ANALYZE` to review and refine query performance.


##Practice Questions
### Easy Level
1. Retrieve the names of all tracks that have more than 1 billion streams.
2. List all albums along with their respective artists.
3. Get the total number of comments for tracks where `licensed = TRUE`.
4. Find all tracks that belong to the album type `single`.
5. Count the total number of tracks by each artist.

### Medium Level
1. Calculate the average danceability of tracks in each album.
2. Find the top 5 tracks with the highest energy values.
3. List all tracks along with their views and likes where `official_video = TRUE`.
4. For each album, calculate the total views of all associated tracks.
5. Retrieve the track names that have been streamed on Spotify more than YouTube.

### Advanced Level
1. Find the top 3 most-viewed tracks for each artist using window functions.
2. Write a query to find tracks where the liveness score is above the average.
3. **Use a `WITH` clause to calculate the difference between the highest and lowest energy values for tracks in each album.**
4. Find tracks where the energy-to-liveness ratio is greater than 1.2.
5. Calculate the cumulative sum of likes for tracks ordered by the number of views, using window functions.






## Technology Stack
- **Database**: PostgreSQL
- **SQL Queries**: DDL, DML, Aggregations, Joins, Subqueries, Window Functions
- **Tools**: =PostgreSQL (via Supabase)

## How to Run the Project
1. Nake project inside supabase.
2. Create a table for the dataset.
3. Insert the sample data into the respective tables(Manually or through CSV upload).
4. Execute SQL queries to solve the listed problems.
5. Explore query optimization techniques for large datasets.

## Contributing
If you would like to contribute to this project, feel free to fork the repository, submit pull requests, or raise issues.
