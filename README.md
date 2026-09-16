# IPL Ball-by-Ball Data Analysis 🏏

A beginner data analysis project exploring 18 seasons (2008–2026) of Indian Premier League cricket, using ball-by-ball data to uncover batting, bowling, and match-level trends.

## What this project answers

- Who are the all-time top run scorers in IPL history?
- Which bowlers have the best economy rate (min. 300 balls bowled)?
- How does scoring pattern change across an innings — powerplay vs. death overs?
- Does winning the toss actually help a team win the match?
- Deep dive into an individual player's scoring pattern (strike rate, runs-per-ball distribution)

## Dataset

Ball-by-ball IPL data (2008–2026), ~295,000 rows, one row per delivery bowled, including match context (teams, toss, venue, result) in every row.

## Tools & concepts practiced

This was a from-scratch learning project focused on core pandas fundamentals:

- **`groupby()`** — grouping rows by a category (e.g. batter, bowler) before summarizing
- **`.agg()`** — computing multiple aggregate statistics at once
- **Column-wise arithmetic** — deriving new columns (e.g. economy rate) from existing ones
- **Boolean filtering** — e.g. keeping only bowlers with 300+ balls to avoid small-sample noise
- **`drop_duplicates()`** — collapsing ball-level data down to one row per match for match-level questions
- **`matplotlib` / pandas `.plot()`** — bar charts, line charts, and pie charts for visual storytelling

## Key findings

- Toss winners go on to win the match only ~50.5% of the time — essentially a coin flip, despite the common belief that toss matters a lot.
- Scoring rate is visibly higher in the powerplay (overs 1–6) and death overs (16–20) compared to the middle overs, reflecting fielding restrictions and end-game aggression.
- V Kohli leads all-time run scoring across IPL history.


## Sample output
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/2dee8574-c340-4a89-acdf-c6bfefd4cff7" />
<img width="846" height="547" alt="image" src="https://github.com/user-attachments/assets/6f681a99-66d5-4496-925f-6cbd7a0e33b2" />



Built as a hands-on learning project to practice pandas fundamentals . 
thank you!
