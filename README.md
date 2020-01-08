# Game26

In this game, the number of decks (here it is 1) and the number of players (here it is 5) are passed in by the user. One of the players will be a dealer, and the rest are the players. Initially, all the players are given 2 cards each and they can ask for more cards if the sum of their current cards is less than the value(here it is 21).

The game will be simulated until all the players cannot ask for more cards and the player that has the sum closest to 26 will be the winner. If the dealer and a player have the same value then the dealer will be the winner. There can be multiple players who are winners if they have the same value. 

Programming concepts: Arrays, ArrayLists, and Object-Oriented Programming

Object-Oriented Programming concepts:

Abstraction(private identifiers were used to hide the complexity and only change the properties inside the class), 

Encapsulation (the 3 classes: Card, Player, and Dealer contained their own private instance variables and methods to reduce complexity and make the code more reusable), 

Polymorphism (The toString() method of the Java Object class was overridden in all three classes to have an unique implementation in each class)
