# TicTacToe

> A simple plugin to play tic tac toe in Minecraft.

---

### Table of Contents
You can access different sections from here:

- [Description](#description)
- [Installation](#installation)
- [How To Use](#how-to-use)
- [Author Info](#author-info)

---

## Description

Here we have the source code for the actual plugin, you can change stuff in it, especially if you want to add your SQL server to store the saved games.

[Back To The Top](#TicTacToe)

---

## Installation

The usage is pretty easy. After you're done with the code just compile the tic tac toe class and copy the .jar file from the target folder into your plugins folder in your dedicated server folder.

[Back To The Top](#TicTacToe)

---

## How To Use

#### Starting the game

You can start the game by using /challenge and a name argument which is your freind's name(like "/challenge johnny007".
Note that your friend must be online.

Once you send your challenge request, your freind either can accept or deny and base on his/her respond game will or will not continiue.

#### Placing pieces 

You have 2 options to place your piece:

->First, simply right-click on the block you want to place your piece.

->Second, use command /put followed by a number from 1 to 9.

#### Saving your game 

As you proceed to play, you can save your game by connecting the code to your SQL server.
Note that you can change the url address, username and your password in the source code.
To save your game just use /save command.
The game database is using id with auto increment feature so there is no way that two or more games with same id exist.
You can also load your game by using the /load command and the id that was given to you in previously saved game.


[Back To The Top](#TicTacToe)

---

## Creater Info

I'm a student (currently) in Babol Noshirvani University of Technology and there is a lot that I haven't learned and am trying to overcome these challenges!
Feel free to comment about this repo.

- Main repo - [Minecraft-TICTACTOE](https://github.com/ah-youmk/Minecraft-TICTACTOE)
- Telegram - [@ahyoumk](https://t.me/ahyoumk)

[Back To The Top](#TicTacToe)
