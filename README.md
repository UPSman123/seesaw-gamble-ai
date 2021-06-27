# seesaw-gamble-ai
This project tries to find an optimal strategy to the seesaw game through machine learning.

## The Seesaw Game
As far as I know I am the first to come up with this game however, it wouldn't surprise me if I'm not. If you do have any information about similar 'games' please feel free to contace me at UPSman123@protonmail.com.

### The rules
The game is all about guessing how much your opponent(s) are going to bet so you can just barely overbid them.
* At the start of the game every player get a sum of currency.
* The game is devided into rounds. Each round all players make a bet with their currency.
* Everyone lozes what they bet but only the winner gets a point.
* After the last round the player with the most points wins.
  * It is imporant to note that the currency and the points are seperate.
* If a player runs out of currency before the end of the game they simply can't bet anymore.
* If all players run out before the last round the game ends early.
* If there are 2 players who both made the highest bet in a round (they bet the same amount) the round is discarted and the bets are refunded.
  * If the round is discarted it is not played again, the game simply moves on to the next round.
* If at the end of the game there are multiple players with the highest number of points the win goes to the player with the most remaining currency.
* If the players also have the same amount of remaining currency the win is shared amoung them.

### Alterations
Of course there are many possible alterations to this game.
Some might get implemented in the future but currently there are no plans to do so.
Possible alteration might include:
* Different handling of edgecases
* Rewarding the winner of a round with currency
* Offering a second place reward for games with more than 2 players.
