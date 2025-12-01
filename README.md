# MIST4610-Project2

**Team Members:**
1. Jake Cheong [@JakeCheong](https://github.com/thejakech)
2. Brian Kim [@Briandjk](https://github.com/Briandjk)
3. Bethel Mekuria [@bethelmekuria](https://github.com/bethelmeku)
4. Eric Xu [@ericxu888888888](https://github.com/ericxu888888888)
5. Liam McKenna [@LiamMcKenna](https://github.com/LiamPMcKenna04)

# Description:
This college tennis database is designed to manage and analyze all major aspects of a university-level tennis database through an organized system for managing teams, players, coaches, conferences, matches, and tournaments. It captures essential player and team details, supports dynamic roster changes across seasons, and documents coaching assignments and conference alignment. Match participation is recorded for both teams and individual athletes, while tournament results and seasonal rankings offer a clear view of competitive performance. By connecting teams, players, matches, and tournaments, the database delivers a unified structure for overseeing tennis operations and evaluating outcomes.
<img width="1600" height="1260" alt="project2dataModel" src="https://github.com/user-attachments/assets/27e6629a-05db-44dc-a675-994841d8bf6b" />
Team: Stores team information such as college name, division, assigned coach, and conference affiliation.

Coach: Holds details about each coach, including name and title, and identifies which conference they belong to.

Conference: Categorizes teams by conference and classification to organize competition levels.

Player: Contains player information like name, age, gender, and class year.

TeamRoster: Represents roster assignments, showing which players belong to which teams during a given season.

Tournament: Tracks tournament details, including date, location, and season.

TournamentResult: Records tournament outcomes by linking teams to tournaments and documenting the winner.

Match: Stores match details such as round, date, season, and associated tournament.

MatchTeam: Indicates which teams participate in each match.

MatchPlayer: Tracks individual player participation in matches.

Ranking: Records seasonal team and player rankings to evaluate competitive performance.


# Data Dictionary:
**Team**

<img width="697" height="239" alt="Screenshot 2025-11-30 at 8 04 30 PM" src="https://github.com/user-attachments/assets/6e5a4893-3c4a-4aa6-a9f0-8a3a7fa3df07" />

**Coach**

<img width="700" height="208" alt="Screenshot 2025-11-30 at 7 52 33 PM" src="https://github.com/user-attachments/assets/571519e1-7eab-4c35-be96-ce314a4d6a87" />

**Conference**

<img width="700" height="128" alt="Screenshot 2025-11-30 at 7 52 50 PM" src="https://github.com/user-attachments/assets/0276e869-2843-477a-a29f-177f6944c82a" />

**Player**

<img width="700" height="254" alt="Screenshot 2025-11-30 at 7 53 38 PM" src="https://github.com/user-attachments/assets/348ff6e6-0ad2-4940-b873-d76ffce2bca3" />

**TeamRoster**

<img width="700" height="112" alt="Screenshot 2025-11-30 at 7 53 54 PM" src="https://github.com/user-attachments/assets/c41f687a-958a-461d-8ff5-044fa8d7ed3b" />

**Tournament**

<img width="700" height="183" alt="Screenshot 2025-11-30 at 7 54 28 PM" src="https://github.com/user-attachments/assets/618b7bb9-e5b1-49c3-a80d-18f1bbb316f8" />

**TournamentResult**

<img width="700" height="183" alt="Screenshot 2025-11-30 at 7 54 49 PM" src="https://github.com/user-attachments/assets/285585d9-b4ee-4ddd-8a5e-2845207deaad" />

**Match**

<img width="700" height="239" alt="Screenshot 2025-11-30 at 7 55 07 PM" src="https://github.com/user-attachments/assets/00e0feb9-ece2-4977-b40d-f67b082836a9" />

**MatchTeam**

<img width="692" height="112" alt="Screenshot 2025-11-30 at 8 02 08 PM" src="https://github.com/user-attachments/assets/6f3ceb10-f220-4e97-917a-0fcf3624c0ec" />

**MatchPlayer**

<img width="700" height="112" alt="Screenshot 2025-11-30 at 7 58 37 PM" src="https://github.com/user-attachments/assets/5e7c3130-f66e-4e56-bdf4-3ec2680354a0" />

**Ranking**

<img width="700" height="241" alt="Screenshot 2025-11-30 at 7 57 58 PM" src="https://github.com/user-attachments/assets/c2b675af-e2d9-4e2c-a8ac-3a10c8b4a9eb" />

# Queries:
**Query 1**: Enables comparison of how strong each conference is in NCAA tournaments, which is useful for conference leadership and athletic directors when evaluating overall competitiveness.

**Query 2**: Helps conference officials or athletic directors evaluate which coaches are most successful in postseason play within a specific conference.

**Query 3**: Allows coaches and recruiting coordinators to see which programs are most at risk of losing a large share of their roster to graduation, guiding recruiting and scholarship planning.
<img width="1270" height="715" alt="image" src="https://github.com/user-attachments/assets/8112ecb1-e6ec-4442-924c-f9ee6bd5d5d1" />


**Query 4**: Gives coaches and analysts insight into how deep each team’s lineup was in the national championship match and whether they relied on a balanced mix of classes or mainly older players.
<img width="737" height="502" alt="image" src="https://github.com/user-attachments/assets/7318adb3-d559-44ea-9a5b-2e069b322762" />


**Query 5**: A manager or coach needs to track which players contribute the most in matches. This helps identify reliable players, and with making lineup decisions. (Returns 97 Rows)

<img width="571" height="693" alt="image" src="https://github.com/user-attachments/assets/1782754b-b4a9-4b03-baf2-5e2478f60600" />

### continued to bottom of results...

<img width="586" height="457" alt="image" src="https://github.com/user-attachments/assets/927eab0b-410d-4578-82fa-c2801a22f29d" />


# Tableau Visualizations:
**1. Which players participated in the most matches?**
   
   <img width="842" height="554" alt="Screenshot 2025-11-30 at 10 25 07 PM" src="https://github.com/user-attachments/assets/835511bb-ab85-4454-a686-340900a738ff" />

     **Description**: This visualization helps coaches, analysts, and team managers understand each player's workload. Some players may be overused, and that can be a risk of injury, while others may not be getting enough competitive matches. We used a bar chart and sorted it to rank players from most active to least active.



**2. Which teams play the most matches, and how do their matches distribute across rounds (Final, Semifinal, Quarterfinal)?**

   <img width="837" height="571" alt="Screenshot 2025-11-30 at 10 37 12 PM" src="https://github.com/user-attachments/assets/a37ad1d7-a7c8-4184-b4e4-6f0901e8dd3a" />

      **Description**: This visualization looks at team participation across the different rounds of tournaments (Ornage=Final, Green=Semifinal, Red=Quarterfinal, and Blue=Null). For managers and coaches, this is important because it highlights how deep each team advances in a competition. The teams that reach the final rounds consistently show stronger performance and have a competitive advantage, while the teams that get eliminated in early rounds may need some adjustments. This breakdown can also help track progress over time. We chose the stacked bar chart to visualize this because it provides a more inclusive view than a simpler bar chart.



**3. How does a player’s class year relate to participation in different tournament rounds?**
   
   <img width="441" height="565" alt="Screenshot 2025-11-30 at 10 47 29 PM" src="https://github.com/user-attachments/assets/669df8c5-4aed-4301-bfdf-5ce34b9aa977" />

      **Description**: This visualization helps coaches understand how experience level influences player involvement in different stages of the tournament. Each dot on the graph represents a player in that tournament round. With the Class Year on one axis and Round on another axis, the scatter plot gives a clear view of which groups are participating at each level of the tournament. 

# TABLEAU DASHBOARD

<img width="1298" height="1370" alt="MIST 4610 PROJECT 2" src="https://github.com/user-attachments/assets/be1da138-31d6-4cbe-8c24-b105273fe082" />

   


   

