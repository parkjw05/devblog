---
layout: post
title:  "Planning a new Hangul Combination Puzzle"
date:   2022-12-27 12:00:00 +0900
categories: development
---


## Introduction

This game is developed from the Korean Language, Hangul. Hangul can create various of combinations throughout all characters and this puzzle focuses on that specific strngth of Hangul.

## Puzzle Description

![hangulgame_description](/devblog/assets/hangulgame_description.png)

The ultimate goal of this puzzle is to make as many combinations as possible, utilizing the Hangul characters which are provided in the four boxes.

## Puzzle Rules

![hangulgame_process](/devblog/assets/hangulgame_process.png)

Every round, four boxes are summoned, while surrounding the red box. Then, all four boxes are instantly and randomly filled with its Korean character for the round. Each characters must be used only once and there is an answer box located below the puzzle. In order for the player to use a character, one has to click or tap on it and once a character is used, it disappears from its box. Finally in order of being clicked, the charcters move down to the answer box and are combined into a word, if possible.

## Puzzle Completion

![hangulgame_example](/devblog/assets/hangulgame_example.png)

For each round, there will be a specific word, chosen to determine the success/failure of the given round. However, the players are not informed how many possible combinaations there are: there could be 1 or 10 words. As players move on to higher level rounds, there could be more combinations available and those words could be more complicated and more number of combinations may be required in order to "pass" the round. The red box in the middle is used to project the player's score during the game and depending on the number of tries or the amount of time that the player took, those may give penalties by multiple ways, such as giving less amount of points. In addition, the "X" in the middle changes to an "O", when the player clears the stage.
