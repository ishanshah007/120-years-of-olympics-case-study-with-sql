# 120 Years of Olympics Data Case Study with SQL

I conducted a comprehensive case study on a dataset that contained information about all Olympic games played from Athens 1896 to Rio 2016. The dataset includes two main tables: `olympics_history` and `noc_regions`.

## Dataset Information

- **Dataset Source:** [Kaggle - 120 Years of Olympic History (Athletes and Results)](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
- **Tables:**
  - `olympics_history`: Individual athlete information in Olympic events.
  - `noc_regions`: National Olympics participant and their regions.

## Dataset Overview

- **athlete_events.csv:**
  - Total Rows: 243566
  - Total Columns: 15
  - Each row corresponds to an individual athlete competing in an Olympic event.


  | Column | Description |
  |--------|-------------|
  | ID     | Unique number for each athlete |
  | Name   | Athlete's name |
  | Sex    | M or F |
  | Age    | Integer |
  | Height | In centimeters |
  | Weight | In kilograms |
  | Team   | Team name |
  | NOC    | National Olympic Committee 3-letter code |
  | Games  | Year and season |
  | Year   | Integer |
  | Season | Summer or Winter |
  | City   | Host city |
  | Sport  | Sport |
  | Event  | Event |
  | Medal  | Gold, Silver, Bronze, or NA |

- **noc_regions:**
  - Total Rows: 230
  - Total Columns: 3


    | Column | Description |
    |--------|-------------|
    | NOC    | National Olympic Committee 3-letter code |
    | Region | Region name |
    | Notes  | Additional information about the region |

## 16 Questions Explored

From the dataset, I explored the following 16 questions utilizing MySQL:

1. How many Olympic games have been held?
2. List down all Olympic games held so far.
3. Mention the total number of nations that participated in each Olympic game.
4. Which year saw the highest and lowest number of countries participating in the Olympics?
5. Which nation has participated in all of the Olympic games?
6. Identify the sport played in all Summer Olympics.
7. Which sports were played only once in the Olympics?
8. Fetch the total number of sports played in each Olympic game.
9. Fetch details of the oldest athletes to win a gold medal.
10. Fetch the top 5 athletes who have won the most gold medals.
11. Fetch the top 5 athletes who have won the most medals (gold/silver/bronze).
12. Fetch the top 5 most successful countries in the Olympics based on the number of medals won.
13. List down total gold, silver, and bronze medals won by each country.
14. Which countries have never won a gold medal but have won silver/bronze medals?
15. In which Sport/event did India win the highest number of medals?
16. Break down all Olympic games where India won a medal for Hockey and the number of medals in each Olympic game.

## References
- https://www.youtube.com/watch?v=XruOBp7yPXU
