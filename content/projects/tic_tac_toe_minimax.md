+++ 
draft = false
date = 2022-09-18T21:09:44+05:30
title = "Solving Tic-Tac-Toe using Minimax Algorithm"
description = ""
slug = ""
authors = []
tags = ["Game AI","Minimax"]
categories = ["CLASSIC AI"]
externalLink = ""
series = [2]
+++

# Introduction
Back in the day, I wrote an AI program that used the minimax algorithm to power the bot to play against humans in the classic Tic Tac Toe game. I still remember it when I asked my friends to play against my program and we were all excited to see the interesting choices that the program made and occasionally defended itself to push the game to a draw.  Minimax Algorithm was my first exposure to classic AI algorithms and even after spending years with the modern machine learning algorithm, I still think it's a simple, intuitive algorithm and closely mimics how you would think ahead in time while playing the game. Very recently, I got the chance to revisit the game from the lens of Game Theory and found myself appreciating the beauty of the algorithm even more. I hope you will enjoy this blog and appreciate this classical AI algorithm, just like I did. Please feel free to contact me if you have any feedback or suggestions.

The minimax algorithm is a classic decision-making technique used in artificial intelligence and game theory. It is a powerful tool that allows a computer to make optimal decisions in a situation where there are two opposing players.

At its core, the minimax algorithm is a recursive search algorithm that considers all possible moves by both players and selects the move that will maximize the player's score and minimize the opponent's score. This is done by simulating the outcome of each possible move and assigning a value to each outcome based on the relative strength of the resulting position.

The minimax algorithm is typically used in games where both players are trying to maximize their own scores and minimize the other player's score. Examples of such games include chess, checkers, and tic-tac-toe. In these games, the minimax algorithm allows the computer to make optimal decisions by considering all possible moves and selecting the one that will result in the best outcome for the player.

To implement the minimax algorithm, we first need to define a set of rules for the game that we are playing. These rules define the possible moves that can be made, the conditions under which the game ends, and the scoring system. Once we have defined these rules, we can begin to implement the minimax algorithm.

First, we need to create a function that will evaluate the current game state. This function will take the current game state as input and return a score that represents the relative strength of the position. The score should be positive if the position is favorable for the player, and negative if it is favorable for the opponent.

Next, we need to create a function that will generate all possible moves from the current game state. This function will take the current game state as input and return a list of all possible moves that can be made from that state.

Once we have these two functions, we can implement the minimax algorithm itself. This is done using a recursive search that considers all possible moves and their resulting game states. For each possible move, the algorithm will evaluate the resulting game state using the evaluation function, and then recursively call itself on each resulting game state to generate all possible moves from that state.

Once all possible moves and resulting game states have been considered, the minimax algorithm will select the move that leads to the game state with the highest score for the player and the lowest score for the opponent. This is the optimal decision, as it maximizes the player's score and minimizes the opponent's score.

In conclusion, the minimax algorithm is a powerful tool that allows a computer to make optimal decisions in situations where there are two opposing players. By simulating the outcome of each possible move and assigning a value to each outcome, the minimax algorithm can determine the best move to make in any given situation. This makes it a valuable tool for artificial intelligence and game theory.

# Briefly Explain the problem statement
qweqweqw
# Computational representation of the game

# Explain MiniMax Algorithm

# Explain how do we use Minimax to solve TTT

# challenges with basic Minimax Version

# Runbook for code.

# Conclude
