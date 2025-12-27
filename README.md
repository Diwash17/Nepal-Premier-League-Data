# Nepal Premier League (NPL) Dataset 

This dataset contains detailed information about the Nepal Premier League (NPL) 2024/25 season. It includes high-level tournament summaries and detailed ball-by-ball data for each match, enabling comprehensive analysis.

---

## Dataset Overview

The dataset is split into two parts:

1. **Tournament Summary Data (`Nepal_Premier_League.csv`)**  
   High-level details for each match in the tournament.

2. **Ball-by-Ball Data (`ball_by_ball.csv`)**  
   Detailed ball-by-ball information for every match.

---

## Dataset Files and Columns

### 1. Tournament Summary Data (`Nepal_Premier_League.csv`)

#### Columns:
- **`match_no`**: Unique identifier for each match.
- **`team_1`**: Name of the first team.
- **`team_2`**: Name of the second team.
- **`season`**: The season or year the match was played.
- **`player_of_the_match`**: The player awarded for their outstanding performance.
- **`toss_winner`**: Team that won the toss.
- **`toss_decision`**: Decision made by the toss-winning team (bat/field).
- **`target`**: Target score set for the chasing team.
- **`winner_team`**: Name of the team that won the match.
- **`won_by_margin`**: Margin by which the winning team secured victory.
- **`umpire_1`**: Name of the first umpire.
- **`umpire_2`**: Name of the second umpire.
- **`tv_umpire`**: Name of the TV umpire.
- **`match_referee`**: Name of the match referee.

---

### 2. Ball-by-Ball Data (`ball_by_ball.csv`)

#### Columns:
- **`match_no`**: Match identifier linking to the `Nepal_Premier_League.csv`.
- **`inning`**: Inning number (1 or 2).
- **`date`**: Date of the match.
- **`batting_team`**: Name of the batting team.
- **`bowling_team`**: Name of the bowling team.
- **`over`**: Over number.
- **`ball`**: Ball number within the over.
- **`batter`**: Name of the batsman on strike.
- **`bowler`**: Name of the bowler.
- **`non_striker`**: Name of the non-striking batsman.
- **`batsman_runs`**: Runs scored by the batsman on the ball.
- **`extra_runs`**: Additional runs due to extras.
- **`total_runs`**: Total runs scored in the ball (batsman + extras).
- **`extras_type`**: Type of extras (e.g., wides, no-balls).
- **`is_wicket`**: Indicates whether a wicket fell on the ball.
- **`player_dismissed`**: Name of the player dismissed (if applicable).
- **`dismissal_kind`**: Type of dismissal (e.g., bowled, caught).
- **`fielder`**: Name of the fielder involved in the dismissal (if applicable).

## Data Source
- **`Tournament`**: Espncricinfo
- **`ball by ball`**: Cricsheet






