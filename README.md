# MJ vs The King
![image](https://user-images.githubusercontent.com/94020684/215630836-7c1ded66-b492-4e47-a956-de4dbaa556ad.png)
# Analysis
- Statistical Modeling
- EDA
- T-test
- Distributions
- Summary Statistics
# Skills Used
- Python:
  - Feature engineering
  - Data Analysis
  - Querying 
  - Web-scraping
  - Feature engineering
  - Data Analysis
  - Loops
  - Iterations
  - Functions
  - Data Structures

- SQL:
  - Data Analysis
  - Querying
  - Creating Databases
  - SQL connector
  - Reporting
  - Feature Engineering
# Why I chose the technologies and what did I gain from it?
With a passion for data and arriving conclusions I have always wanted to gain more experience with different technologies as I grow. This particular project could have been done with an excel sheet but I wanted to apply some of the knowledge I have picked up through codeacademy to an analysis. The technologies I chose were Python and SQL. Python is great for collection of data using the bs4 package so I applied that and was able to loop through a series of names and different link ids to get the span of time the player played in the nba. I then took that data and stored it in SQL so it could be easily queried from juypter notebook. Within python I was able to utilize the queries in SQL to my advantage when performing data manipulation. This made it seamless to create different visualizations. 
From this experience I gained a lot of knowledge about working through a clean notebook. I also picked up man data engineering skills while working with different structures to make the analysis smooth. This also helped me refresh on some familiar topics such as matplotlib, pandas and seaborn. In this analysis I used new visualizations to explore the data. 

 ## Project ?
 The goal of this project was to get a deep understanding of each players statistics over the course of their career. This project takes deep dives into players performance over the years and how they stack up agaisnt eachother. 
 
 ## The Question
 # Who is the greatest player?
 
 Michael Jordan during his career was able to accomplish a lot finishing with total of 32,292 points in his 15 year career playing 1072 games. Jordan was able to collect a total of 6 rings throughout that time. Lebron is currently still in the league and has more potential records to break. Up until 2022 Lebron has been able to play in 1521 games scoring a sum of 37,062 points with 4 rings in 18 years. This is a big difference in time and points. 
# Player Present vs Not
While Jordan was playing he missed a total of 14 games while fully healthy on roster. Out of those 14 games 10 of them were losses and 4 were wins, so without Jordan his teammates posted a 29% chance of success. When Jordan was in the game his record was 706-266 in the regular season with a 66% win rate. 
Lebron from 2004-2022 season has missed a total of 155 games. Oout of the 155 games Lebrons teammates went 54-101 with a 35% win rate. While Lebron is in he is 894-472 with a 65% rate of success. 
Lebron has missed an astonishing amount of games in his career (10.19%) compared to Jordan with 14 (1.30%). Throughout these missed games each team Lebron and Jordan played on suffered a vary simliar amount with similiar records of the fellow teammates. 
# Year over Year Performances 
Lebron and Jordan had both performed amoungst the best in each season but at what age were they the most dominate? Lebron was best at age 21 for scoring averaging a total of 29 points per game. Jordan scored his highest at age 25 averaging 36 points per game. These years Lebron also shot the ball the most in his career averaging almost 22 field goal attempts. Jordan at age 25 was also playing the most he has every in his life average almost 41 minutes per game.
# Acheivements Over Same # of Games

We can see over the years when comparing statistics that Michael Jordan lead Lebron over the same amount of games. Jordan was ahead of Lebron by over 5 k points, over 800 steals, 100+ blocks, and with only around 500 extra minutes played. Lebron lead over Jordan with 100 more rebounds, over 100+ assists and 800 3 pointers. It is very evident with these visuals that Lebron and Jordan were different players. Lebron is more of an outside shooter that distributes the ball very well considering he still scores a lot with high assists. Michael Jordan was a scrapier defensive player with higher steals which also caused Jordan to get a lot of steals in his career. Jordan did not spend a plot of time beyond the 3 point line as he kept his game within and had a lot of success doing so. The difference is that Michael Jordan is 3 years older in this in comparison to Lebron who started to play straight out of high school at age 18. The next question is who was better by age? 
![image](https://user-images.githubusercontent.com/94020684/215641365-c2fdd62b-1d6b-4e99-bea3-420831f45d32.png)
![image](https://user-images.githubusercontent.com/94020684/215641415-e05d2ad5-2037-4aaa-84a8-fda81b21d5d7.png)
![image](https://user-images.githubusercontent.com/94020684/215641455-f2e7956b-1cbb-48c9-bdb3-7a455575dead.png)

# Better Shooter ?

Lebron through his career has been able to maintain a 50.5% field goal percentage comared to Jordans 49.6%. Jordan has been able to shoot better at the line with a 83% rate of success compared to Lebrons 73%. Lebron is much better from long range with a 31% success rate comapred to Jordans 27%. 
![output_66_3](https://user-images.githubusercontent.com/94020684/215642680-1952c232-77c0-44b1-a316-bfd80948a24d.png)
![output_66_5](https://user-images.githubusercontent.com/94020684/215642727-3b736b99-5cff-4ea3-930d-337772a117e3.png)
![output_66_1](https://user-images.githubusercontent.com/94020684/215642746-4a1d76f6-c6b9-4118-ab25-1a258423404e.png)

# Consistency

Were going to look at how Lebron in his first 1072 games played compared to Jordan. Lebron was more consistent than Jordan in how many points he scored per night. Jordan did have higher average points scored and the highest amount of points scored in a game being 69 compared to Lebrons 61. 
![image](https://user-images.githubusercontent.com/94020684/215645930-dcf08485-894c-4e28-81a0-17668ececac8.png)

You can also see here the overlay of Lebrons consistency by not as high scoring as Jordan through the first 1072 regular season games of eachs career. Lebron has spikes in the mid 20s compared to jordans spikes you see in the 30s and 40s. Jordan has a fewer amount of these games scored but much greater than Lebron. I was also able to run a t-test on the data to find out that their is a significant different between the distributions. The p-value came out to be 2.66 and t-stat at 12.5 which was enough to reject the null of no difference and go with alternative. 
![image](https://user-images.githubusercontent.com/94020684/215646133-95a7b686-37d9-4cac-bad8-d714a51f1beb.png)

# Conclusion
Letting the data speak for itself it shows that Jordan had a much greater ability to score than Lebron did. Jordan did lack in essentially every other category in basketball except scoring. Jordan seemed to be taking a lot of shots to go along with the amount of points he scored but he kept it close. Lebron is more versitile in his scoring ability being effective inside and outside the arc. When it came to defense Jordan was able to tally up a much higher amount of steals than Lebron but that also resulted in a lot of foul calls. Jordan did also have the up on amount of blocks. 
If you want a player that is eager to score then Michael Jordan is the player that will do it. Lebron is a general of the floor with high averages in every statistical category but not the best.
