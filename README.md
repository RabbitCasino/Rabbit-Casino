# Rabbit Casino

![project image](https://github.com/RabbitCasino/Rabbit-Casino/tree/main/raw/banner.jpg)

## Description

Rabbit Casino is an online casino where you can find unique games but above all Rabbit Casino is an exciting experiment that proves that it is possible to create a new type of online casino where the player can feel safe because the winnings are guaranteed by a system that "seals" the method of creating the games.
Open your Tor browser and come visit us here

http://omiz35ogxn55z5sxivse7nbpssjvdc2td7cs74xheimrntfpv2fqrmid.onion


## The provably fair system

### Random numbers

The system uses random numbers to generate games. A random number is a number chosen by chance, randomly, from a set of numbers. All the numbers in a specified distribution have equal probability of being chosen randomly.
Each single game has its own way of calculating the outcome from a given random number explained in detail on the game's page.

### Salt and pepper

Salt and pepper... this is our recipe for demonstrating the correctness of the draws and the impossibility of deceiving the player by the system.

Before you play any game, the system prepares a secret random number and calculates its digital signature. For security reasons you cannot know the exact number but you can always see its digital signature (or hash). The generated random number is kept hidden until it is used, i.e. until you decide to play a game.

These rules ensures that:
- the random number whose digital signature you can see is the only number that the system can use to generate the next game
- the random number remains the same whichever game you choose, this guarantees the neutrality of the chosen number towards games
- it is impossible for the system to use any random number other than the one already drawn; in order to do this, the system would have to find another number whose digital signature exactly matches the one displayed to the player... that's impossible.

https://github.com/RabbitCasino/Rabbit-Casino/tree/main/raw/pfs.mp4
