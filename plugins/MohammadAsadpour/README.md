# TicTacToe

> A Tic-Tac-Toe Plugin for Minecraft (Spigot)

![photo_2022-07-08_21-34-41](https://user-images.githubusercontent.com/107719378/178038077-7ad835c2-3c77-4187-9584-fb1d85ac8f5a.jpg)

---

### Table of Contents

- [Description](#description)
- [Installation](#installation)
- [How To Use](#how-to-use)
- [End Game](#end-game)
- [Features For The Future](#features-for-the-future)
- [Author Info](#author-info)

---

## Description

A plugin for Minecraft, which allows players to challenge others and compete in the classic game of Tic-Tac-Toe!

[Back To The Top](#tictactoe)

---

## Installation

To use this plugin, copy the .jar file to the "plugins" folder of your Spigot server (version 1.18.2). Then start the server, and enjoy the game!

[Back To The Top](#tictactoe)

---

## How To Use

#### Starting the game (/challenge "anotherPlayer") -> (/accept) or (/deny)

To start the game, use the command ( /challenge "anotherPlayer" ), and call another player. 

        NOTE: In order to be able to call the /challenge command, your surrounding area must be empty.
        
If the player is online, a message is sent to them, and they have 20 seconds to either /accept or /deny.
If the plays accepts the challenge, both of you will be teleported to a game arena, where you will make your moves, starting with you.
  
        NOTE: The game is designed to be able to handle multiple game at the save time.
              However, due to the lack of resources, this feauture is not tested yet.

#### Placing pieces (/put "number")
  
You can place your move in two ways:
  1. By using the command ( /put "number" ), with a number between 1 and 9
  2. By right clicking on the block of your choice
  
By doing this, the block will change color to the color of the player.
  1. The player who started the game will be RED.
  2. The player who was challenged will be BLUE.
  
#### Saving a game & Loading in the future (/save) & (/load "gameName")

Players can use the command /save, to save the game they are currently playing. After this, the arena will be destroyed, 
and a message will annouce to the players a game name which they can use to later continue the game with the command ( /load "gameName" ).

#### Viewing scores using Scoreboard (/scoreboard) & (/scoreboard clear)

The plugin allows each player to see the amount of times that they won, lost, or tied with another player.
  1. By calling the command /scoreboard, you can view your own.
  2. By calling the command /scoreboard oncemore, you can hide it.
  3. By calling the command ( /scoreboard clear ), you can clear your scoreboard.

[Back To The Top](#tictactoe)
  
---

## End Game
  
  #### If someone wins:
          1. A message will be sent to the winner and loser's screen, anouncing their outcome!
          2. Lots of firework will be thrown in to the air, set to the color of the winner!
          3. The arena will be destroyed, and the players can pick up the leftover material!
          4. And for the most fun, a hologram will forver mark the winner's name in the server for all to see, forever!
  #### If the game ends with a tie:
          1. A message will be sent to both player's screen, anouncing the tie!
          2. The arena will still be destroyed here, and the players can still pickup the left material!
          3. The hologram will announce that two players tied at a game, right on this spot!
  
  [Back To The Top](#tictactoe)
  
---

## Features For The Future
  
Here are some of the features that will be added to the plugin in near future:
    
#### Database
    Currently, the game uses serialization to save the files and load games. But in the future, the game will use a database to save the games.

#### No Strangers Allowed
    When two players are playing a game, no one else can step foot on their arena. If they do so, they will be thrown out!
        
#### The Winner's Gift
    Currently, any player can pick up the leftover items after the arena is blown up. But, in a future version, it will become so that only the winner can pick up
    the items as his winning gift. In case of a tie, both players will be allowed to pick the items up, and any other player in the server will be unable to.
        
#### Allowing /accept & /deny when asked to continue a game
    Currently, there is a problem with /load. Although in the messages, it says that you can /accept or /deny a load command, when a player calls the load command, 
    the second player will be directly teleported to them, without being asked for their choice. This bug will be fixed in the near future, and the players can chose
    whether or not they want to continue an old game.
  
#### When a players leaves and returns to the server
    For some reason, when a player leaves the server and returns, they can no longer use the plugin commands. This bug will also be fixed in the near future.
  
[Back To The Top](#tictactoe)
  
---

## Author Info

I'm Mohammad Asadpour, a computer engineering student at the Babol Noshirvani University of Technology (BNUT or NIT). I made this plugin as the final Project of my Advanced Programming course. Even though I am a beginner in the Coding World, it has been an interesting ride so far, despite the hardships that came with it. But, in the end, as we all know:
        
        All beginnings are hard.
        To begin is easy; To persist is art.

[Back To The Top](#tictactoe)
