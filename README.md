# pyFootball
A python based Football (or soccer) management simulation game. Currently in development as a side project that I'll intermittently work on while learning python and working on other java projects. The game is heavily based on [Football Manager](http://www.footballmanager.com/) by Sports Interactive, and [Football Chairman](http://www.football-chairman.com/) by Underground Creative.

### Methodology
1. Team Stats
  1. Prestige - How the team supposedly fared in the past, how succesful they once were
  2. Wealth - How much money they have to spend, directly influenced by prestige
  3. Physicality - How physical the team plays, based on composite player physicalities, height, weight, (possibly speed if I include it)
  4. Passing Potential - How well the team is able to play their form of build up, be it short passing or long crosses
  5. xDP, xMP, xAP - expected Defense, Midfield, and Attacking performance; composite of player D/M/A stats
  6. Team Personality - how the team reacts to certain situations, each team may have a different personality base
2. Player Stats
  1. Height & Weight for Physicality
  2. DP, MP, AP - defensive, midfield, attacking performance (based on position of player); can vary due to hidden stats
  3. Hidden stats: Loyalty, Consistency, Injury Proneness(?)

### Tasks
- [x] Simulate the 10 teams, and give ownership of one team to the Player
- [ ] Create 18 players for each team, giving them unique stats, transfer values, and names.
- [ ] Successfully integrate a satisfactory match engine that will provide results for each game along with simulating the other 4 games taking place each match week, including booking, sending offs, and injuries
- [ ] Create an inbox where you'll see your managerial news, team updates, and anything else relevant to the game.
- [ ] Possibly add names and stats to other managers to allow rivalries to form, and also include team rivalries due to proximity, history, similar prestige/wealth.
- [ ] Create a transfer market where you can buy and sell players, and possibly have contract expirations to your own players.

[check me out @ justnaugr.github.io](http://justnaugr.github.io)