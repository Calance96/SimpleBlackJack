# SimpleBlackJack
A simple black jack game (1 human player vs 1 computer player) written with C# using ASP.NET Core 3.1 MVC framework. 

Credits to American Contract Bridge League (ACBL) for the Poker card images. The resources can be found at http://acbl.mybigcommerce.com/52-playing-cards.

The game rules are as follows:
1. The player needs to have at least 16 points in order to stay, otherwise the player needs to draw card from the deck.
1. If the player's points exceed 21, the player is considered lost. If the computer gets more than 21 points, the game is considered draw.
1. If the player gets 21 points in the beginning, the player wins automatically. The same goes to computer.
1. The player hits Charlie Blackjack if the player's points is less than or equal to 21 when the player holds 5 cards (maximum). In such case, the player wins automatically. Otherwise, the computer wins automatically. The same applies to the computer as well.

## Demonstration Picture
![Demo Pic](../media/images/blackjack_demo_pic.png?raw=true)
