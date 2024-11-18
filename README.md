# Tennis Kata

This kata is about modeling a tennis match :).

Scorekeeping in tennis can be tricky, which is why the ATP has hired us to build a scoreboard that is able to display the current result of a match.

Our job is to write a "TennisGame" program that contains the scoring system logic and displays the correct result in text format for display on the screens.

When a player wins a point, the program will contain a method that can be called to tell it which player won the point. In addition, the system will receive calls from the screens to a "score()" method that will return the current score. This method should return a text with the result.

This is a summary explaining how scoring works in tennis, but if you need more information you can visit the following
[link](https://en.wikipedia.org/wiki/Tennis#Scoring):

1. A game is won when one of the players wins at least 4 points in total and at least two points more than the opponent.
2. The partial scoring is carried out in a somewhat (BOOM!) "special" way: respectively "Love", "Fifteen", "Thirty", and "Forty".
3. If at least each player has won 3 points and the score is tied, the result is "Deuce".
4. If at least each of the players has won 3 points and one of the players has one more point than his opponent, the result of the game is "Advantage" for the player in the lead.

You only need to report the result of the current game. This is a first development, so sets and games are now out of context.

# Run the tests

1. Install [composer](https://getcomposer.org) locally:

	`curl -sS https://getcomposer.org/installer | php`
2. Install dependencies:

	`php composer.phar install`
3. Run the tests

	`./vendor/bin/phpunit`


# Original author

This repository is simply an adapted version of Emily Bache's original repository located at https://github.com/emilybache/Tennis-Refactoring-Kata
