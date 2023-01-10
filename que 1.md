
Problem Statement 2





About the Data

The "IPL_Ball.csv" file is for ball-by-ball data and it has information of all the 19,3468 balls bowled between the years 2008 and 2020. It has 17 columns.
The "IPL_matches.csv" file contains match-wise data and has data of 816 IPL matches. This table has 17 columns.

## Project
Prerquisites before solving the problem statement
Creating a database in MySQL Commandline Client


```bash
CREATE DATABASE ipl;
```


Using the database
```bash
use ipl;
```
1. Create a table named matches with appropriate data types for columns.

id is used as PRIMARY KEY here
```bash
CREATE TABLE matches(
    id INT PRIMARY KEY,
    city VARCHAR(40),
    date DATE,
    player_of_match VARCHAR(40),
    venue VARCHAR(80),
    neutral_venue INT,
    team1 VARCHAR(80),
    team2 VARCHAR(80),
    toss_winner VARCHAR(80),
    toss_decision VARCHAR(20),
    winner VARCHAR(80),
    result VARCHAR(40),
    result_margin INT,
    eliminator VARCHAR(10),
    method VARCHAR(10),
    umpire1 VARCHAR(40),
    umpire2 VARCHAR(40)
);
```
Then describe the table.
```bash
DESCRIBE matches;
```



![App Screenshot](https://github.com/rh540640/Sports-Analytics/raw/master/describe_matches.png)

