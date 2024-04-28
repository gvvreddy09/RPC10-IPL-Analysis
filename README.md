#  Analyse historical IPL data and provide insights on IPL 2024 for a sports magazine
## Project's Objective
**Sports Basics** is a sports blog company that entered space recently.  They wanted to get more traffic to their website by releasing a special edition magazine on IPL 2024.  This magazine aims to provide interesting insights and facts for fans, analysts, and teams based on the last 3 years' data.

For more details about the project, please check [Challenge_10_IPL_Analysis](https://codebasics.io/challenge/codebasics-resume-project-challenge).

### Data overview
1. dim_match_summary: Contains details about the matches
2. dim_players: Includes information about players such as playing role, batting style, and bowling style...
3. fact_batting_summary: Contains details of batting innings for all the matches that happened
4. fact_bowling_summary: Includes all the details of bowling innings for all the matches that happened


### Tools and Approach
For the primary insights, I used **Python**. Imported datasets to **Power BI** and built a report. Using Snowflake schema constructed a data model. Established inactive relationships between tables and made them active through DAX.

I've created 3 pages for IPL analysis (Overview, Team Performance, and Player Performance) and 2 pages to address secondary insights (Predictions, and Best 11):

Utilized Tooltip's feature of Power BI and highlighted Player's Information, and Match details of the selected team. 

**Key Performance Indicators**
1. Team: Total Matches Played, Total Winnings, Total Loss, Win - Loss ratio, Average Runs scored per match, and Average Wickets taken per match
2. Batting: Innings Played, Not Out, Runs scored, Batting average, Strike rate, boundary %, Balls Faced, High score, Average balls faced, 100s, 50s, 4s, and 6s
3. Bowling: Innings bowled, Overs bowled, Runs conceded, Bowling average, Economy, Strike rate, dot ball %, Wickets taken, 4W, 5W, and Maiden

**Overview:**
1. Team-Wise Key Performance Indicators
2. Player's Performance (Batting and Bowling)

**Team Performance:**
1. Win - Loss ratio of team by year
2. Points Table
3. Balance between bowling and batting
4. Orange and Purple cap players

**Player Performance:**
1. Bowling and Batting analysis

**Important Links**
+ To interact with [Live dashboard](https://app.powerbi.com/view?r=eyJrIjoiNWQ3NmEyNzEtZGUxNy00M2ViLWFjZTEtZWMzYWFmYjc5Njg1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9).
+ [Presentation Link](https://www.youtube.com/watch?v=FlD1Nwta334).

### Insights
1. Top 10 batsmen based on past 3 years total runs scored.
2. Top 10 batsmen based on past 3 years batting average. (min 60 balls faced in each season)
3. Top 10 batsmen based on past 3 years strike rate (min 60 balls faced in each season)
4. Top 10 bowlers based on past 3 years total wickets taken.
5. Top 10 bowlers based on past 3 years bowling average. (min 60 balls bowled in each season)
6. Top 10 bowlers based on past 3 years economy rate. (min 60 balls bowled in each season)
7. Top 5 batsmen based on past 3 years boundary % (fours and sixes). (min 60 balls faced in each season)
8. Top 5 bowlers based on past 3 years dot ball %. (min 60 balls bowled in each season)
9. Top 4 teams based on past 3 years winning %.
10. Top 2 teams with the highest number of wins achieved by chasing targets over the past 3 years.
    
**Predictions**
1. Orange and Purple cap players
2. Top 4 Qualifying teams
3. Winner and Runner-Up
4. Best 11
5. Top 3 All-rounders
