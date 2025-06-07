# movie_vote_casting-using-PowerBI
This Power BI report visualizes movie titles, their reviews (overview), total vote counts, and average votes. It's based on data likely sourced from a platform like TMDb (The Movie Database).

1. 📋 Table (Top Left) – Movie Titles by Vote Count :-
      Displays a list of movies with their respective total vote counts. This helps identify           which movies have received more user engagement.

2. 🔢 KPI Card (Top Center) – Total Vote Count :-
        A large, highlighted number: 759
        This is the sum of all vote counts for the listed movies. It gives a quick, high-level           metric for total audience participation.

3. 🍩 Donut Chart (Top Center Right) – Ratio of Total Vote Count vs Average Vote :-
        Visualizes the proportion between:
        Sum of vote_count (blue – 89.24%)
        Sum of vote_average (purple – 10.76%)
        Shows how the volume of votes dominates compared to their averages, which is important           in understanding raw vs. quality feedback.

4. 📈 Line Chart (Bottom Left) – Vote Averages and Counts per Movie :-
        X-axis: Movie Titles.
        Y-axis: Sum values.
        Two lines represent:
        Sum of vote_average (probably the height of individual ratings across users).
        Sum of vote_count.
        Highlights differences in popularity (votes) versus quality (average scores).

5. 🥧 Pie Chart (Bottom Right) – Avg Votes by Original Language :-
      Slices indicate average votes per movie, grouped by the original language (e.g., it, fr,         en, zh, vi). Helps analyze which language-based content receives higher average                  ratings. For instance, Italian (it) and English (en) dominate.

6. 📂 Data Fields (Right Sidebar) :-
        Fields used in visuals:
             title: Movie name.
             overview: Movie summary.
             original_language: Movie language.
             vote_average: Average user rating.
             vote_count: Total number of votes.

