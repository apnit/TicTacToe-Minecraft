# TicTacToe

> A Tic-Tac-Toe Plugin for Minecraft (Spigot)

![photo_2022-07-08_21-34-41](https://user-images.githubusercontent.com/107719378/178038077-7ad835c2-3c77-4187-9584-fb1d85ac8f5a.jpg)

---

### Table of Contents

- [Description](#description)
- [Installation](#installation)
- [How To Use](#how-to-use)
- [End-Game](#end-game)
- [Author Info](#author-info)

---

## Description

A Tic-Tac-Toe Plugin for Minecraft, which alows players to challenge others and play! 

[Back To The Top](#TicTacToe)

---

## Installation

For using this plugin, copy the .jar file to the Plugins folder of your Spigot server (version 1.18.2), start the server, and enjoy the game!

[Back To The Top](#TicTacToe)

---

## How To Use

#### Starting the game (/challenge "anotherPlayer") -> (/accept) or (/deny)

To start the game, use the command ( /challenge <anotherPlayer> ), and call another player. 
    Remember, in order to be able to call the /challenge command, your surrounding area must be empty.
If the player is online, a message is sent to them, and they have 20 seconds to either /accept or /deny.
If the plays accepts the challenge, both of you will be teleported to a game arena, where you will make your moves, starting with you.
  
        NOTE: The game is programmed to be able to able to handle multiple game at the save time.
              However, due to the lack of resources, this feauture is not tested yet.

#### Placing pieces (/put "number")
  
You can place your move in two ways:
  By using the command ( /put <number> ), with a number between 1 and 9
  By right clicking on the block of your choice
  
By doing this, the block will change color to the color of the player.
  The player who started the game will be RED.
  The player who was challenged will be BLUE.
  
#### Saving a game & Loading in the future (/save) & (/load "gameName")

The plugin allows each player to see the amount of times that they won, lost, or tied with another player.
  By calling the command /scoreboard, you can view your own.
  By calling the command /scoreboard oncemore, you can hide it.
  By calling the command ( /scoreboard clear ), you can clear your scoreboard.


#### Viewing scores using Scoreboard (/scoreboard) & (/scoreboard clear)

The plugin allows each player to see the amount of times that they won, lost, or tied with another player.
  By calling the command /scoreboard, you can view your own.
  By calling the command /scoreboard oncemore, you can hide it.
  By calling the command ( /scoreboard clear ), you can clear your scoreboard.

[Back To The Top](#TicTacToe)
  
---

## End Game
  
  #### If someone wins:
          Looots of Firework will be thrown in the color of the player!
          The arena will be destroyed, and the players can pick up the thrown away material!
          A message will be sent to the winner and loser's screen, anouncing their outcome!
          And for the most fun, a hologram will forver mark the winner's name in the server for all to see!
  #### If the game ends with a tie:
          A message will be sent to both player's screen, anouncing the tie!
          The arena will still be destroyed here, and the players can still pickup the left material!
          The hologram will announce that two players tied at a game, right on this spot!
  
  [Back To The Top](#TicTacToe)
  
---

## Features For The Future
  
Here are some of the cool features that will be added to the plugin in near future:
  
    
#### Database
    Currently, the game uses serialization to save the files and load games. But in the future, the game will use a database to save the games.

#### No Strangers Allowed!
    When two players are playing a game, no one else can step foot on their arena. If they do so, they will be thrown out!
  
#### /accept & /deny when asked to continue a game
    Currently, there is a problem with /load. Although in the messages, it says that you can accept or deny a /load command, when a player calls the load command, 
    the second player will be directly teleported to them, without being asked for their choice. This bug will be fixed in the near future, and the players can chose
    whether or not they want to continue an old game.
  
#### When a players leaves and returns to the server.
    For some reason, when a player leaves the server and returns, they can no longer use the plugin commands. This bug will also be fixed in the near future.
  
[Back To The Top](#TicTacToe)
  
---

## Creater Info

I'm Mohammad Asadpour, a computer engineering student at the Babol Noshirvani University of Technology (BNUT or NIT). I made this plugin as the final Project of
  my Advanced Programming course. I am a beginner in the Coding world, but I had lots of fun already, and I'm looking forward for the future.

[Back To The Top](#TicTacToe)
