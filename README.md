# MafiaCity

MAFIA CITY
The beautiful city of Perugia, Italy is under the control of the Italian Mafia. You and your partner, as agents of the Italian DIA (Direzione Investigativa Antimafia), have been assigned the task of destroying the mafia from within. You both have slithered your way into the Mafia Gang. But, the Mafia boss, Don Hugo Salavanca has been informed that there are 2 undercover spies amongst the present gang members. Your mission, if you choose to accept, is to destroy the Mafia from within whilst using your wit and convincing powers to stay alive.

HOW TO PLAY

Mafia city is a 6-player text-based voting game. The game starts when all 6 players have joined and the admin executes the /start command.

Upon starting, 2 players out of the total 6, will be randomly assigned as undercover agents. The agents will get to know who the other agent is but none of the other players will know who's who.

Agents can talk to each other (privately) using * before their messages. Their aim is to convince the mafia gang members that they are not the agents using their wit and convincing skills while getting the other gang members killed.

Players can /vote one player per chance and the player with the most votes gets killed. In the case of one or more players getting the same amount of votes, one of the players with the most votes gets killed at random.

The Mafia members win when both of the agents have been identified and killed. In this case, all of the mafia members get 200 points.
The agents win when when only 2 players remain alive and atleast one of those two is an agent. In this case, both the agents get 400 points.
In case an agent leaves the room mid-game and if he's alive, the game ends immediately and the gang members win the round (get 200 points) and similarly, In case a gang member leaves the room mid-game and if he's alive, the game ends immediately and the agents win the round (get 400 points)

FEATURES

1.Room join/create system.
2.Admin system (if one player disconnects/leaves a room, automatically the next person becomes the admin)
3.Global chat system, room chat system
4.Personal chat system in rooms (between agents)
5.Single Tab System - A person cannot open the website in two tabs at once(implemented using sessionStorage and cookies)
6.Dark and light themes - A user's preffered theme is stored in localStorage and is saved forever.
7.Voting (/vote ) system.
8.Scoring system.
9.Unique room name, unique playerName in a room.
10.Took care of all the corner cases of all the above points. Fixed all of the known bugs.
11.Add emoji picker to text-input.
12.FIXED RATE LIMIT EXCEEDED error by hosting it from HEROKU CLI instead of from github
13.Responsive Design (using pure CSS)
