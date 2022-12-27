---
layout: post
title:  "Computation Game: Mondrian Puzzle Game Planning and Guide"
date:   2022-12-27 12:00:00 +0900
categories: development
---


## Background

![mondrian_main](/devblog/assets/mondrian_main.png)

The main purpose of the Mondrian Puzzle is to boost people's computation abilities, while having an aesthetically pleasing look and feel as well. The puzzle contains various of squares in different size and colors, organized neatly as shown. One of the goals within the creation of this puzzle was to make each step and round to have its own and unique design.

---

## Successful Attempt

![mondrian_correct](/devblog/assets/mondrian_correct.png)

As the ultimate goal is to get rid of all computable combinations within the puzzle. For each rounds, there are two types of boxes shown: equations as colored boxes and quotients as non-colored boxes. Every attempt starts with clicking or tapping on one of the colored boxes, which then must be followed by finding the correct response to the selected equation. If the correct equation and the answer are matched to each other, they disapper from the screen.

## Failure Attempt

![mondrian_wrong](/devblog/assets/mondrian_wrong.png)

However, if a wrong number is selected as the answer to the equation, the boxes will not cancel out but without any penalties given to the player. Then, the player must re-do and process and try to successfully match the correct equations and the answers to each other.

## Final Attempt

![mondrian_complete](/devblog/assets/mondrian_complete.png)

Once the player successfully clears out all the colored boxes by matching them with correct answers, the player will reach the end of the game. If there are no more colored boxes left or if there is no more time left, the round will terminate, leading the player to the next round and more.
