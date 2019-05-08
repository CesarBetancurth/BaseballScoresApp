# BaseballScoresApp
## Project Android - Baseball Scores App
The game chosen to build for the project Score Keeper App was Baseball.

The __Baseball Scores App__ gives the user the ability to keep track the score of the two teams of Baseball game for Visitor team and Home team, and keep track the general metrics such as innings, balls, strikes and outs.

The app start with the buttons for increase the runs and hits *enabled for visitor team and disabled for home team*, because the visitor team always is the first in bat. Also the button for increase the errors is enabled only for the team that is defending (defensive team). ***This is to help the user avoid mistakes when using the Baseball Scores App.***

# Increase team's score:
1. In the **top** half-inning the buttons "+ RUNS, + HIT" of the visitor team and the button "+ ERR" of the home team are remain enabled.
2. In the **bottom** half-inning the buttons "+ RUNS, + HIT" of the home team and the button "+ ERR" of the visitor team are remain enabled.

# The __Baseball Scores App__ is divided in four parts:
* **First Part:** Displays the general metrics of the game such as the innings, balls, strikes and outs.

* **Second Part:** Shows which half-inning is being played. (One inning consisting of two halves, the top and bottom).  And shows the count of pitches by pitcher in turn.

* **Third Part:** It is divided in two columns, one for each team and shows the score of the Visitor team and Home Team, and this has the buttons for increase the counters score of runs, hits or errors.

* **Fourth Part:** Has the buttons to increase the general metrics of the baseball game.

# Scores and Metrics:
* **Runs:** Increase the runs by 1 using the button "+ RUN"
* **Hits:** Increase the hits by 1 using the button "+ HIT" 
* **Errors:** Increase the errors by 1 using the button "+ ERR"
* **Innings:** The innings increase automatically after the bottom half-inning is end with 3 outs recorded. 
The baseball game is usually composed of nine innings, if scores are tied at the end of nine innings, played extra innings; the counter of extra innings is shows in red.
* **Balls:** Increase the balls by 1 using button "+ BALL" until 4 ball, when the value of the balls is four, the counter of balls and strikes is reset.
* **Strikes:** Increase the strikes by 1 using button "+ STRIKE" until 3 strikes, when the value of strikes is three, increase the count of outs by 1 and the counter of balls and strikes is reset.
* **Outs:** Increase the outs by 1 using button "+ OUT" until 3 outs, when three outs recorded, if this is the top half-inning,  the half switch to bottom half-inning or if this is the bottom half-inning,  the innings increase by 1 and the half switch to top half-inning again.
* **Pitches:** Increase pitches by 1 using button “+ PITCHES"
* **Reset Pitches:** When change a pitcher the count of pitches needs to be reset, use the button “RESET PITCHES”, this count is by pitcher in turn.

* **Reset:** Reset all values of Scoreboard using button “RESET”.
