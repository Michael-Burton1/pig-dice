# _Pig Dice_

#### _Pig: A Simple Dice Game_

#### By _**Jo Miller, Maxwell Meyer, Michael Burton**_

## Technologies Used

* _HTML_
* _CSS_
* _JavaScript_

## Description

_A two player game in which a player rolls a single die repeatedly until either a 1 is rolled or the player decides to "hold"._

## Setup/Installation Requirements

* _Clone this repository to your desktop_
* _Navigate to top level of the directory_
* _Open index.html in your browser_

### Or

[Click here!](https://joanna-miller.github.io/pig-dice/)

## Known Bugs

* _Any known issues_
* _should go here_

## Specifications
```
Describe: Player()
Test: Store new player object within Player Constructor.
Expect: (let player1 = new Player()).toEqual(Player{playerNum:,turnScore:,totalScore:,status:})

Describe: Player.prototype.rollDice()
Test: Get random number between 1 and 6, add to an array to track turn score.
Expect: (player1.rollDice()).toEqual(1, 2, 3, 4, 5, or 6)

Describe: Player.prototype.endTurn()
Test: Record rolled value from turn to Player object.
Expect: (player1.endTurn().toEqual(Player{playerNum:,turnScore: turn value, totalScore:,status}))

Describe: Player.prototype.theScore()
Test:
Expect:

Describe: Player.prototype.theTurnScore()
Test: 
Expect:
```

## License

[MIT](LICENSE.txt)

## Contact Information

_Jo Miller: joannamiller@gmail.com_ <br>
_Maxwell Meyer: maxreadswell@gmail.com_ <br>
_Michael Burton: micbur1@gmail.com_
