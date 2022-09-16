---
layout: post
title: Artificial Intelligence
date: 2022-04-23
description:
img: ai.webp
tags: [Project]
---

These projects were exercises and assignments part of [CSCD84] (Artificial Intelligence).

We learned the basics of efficient search algorthims, constraint satisfaction problems, mini-max backtracking for game based problems, reinforcement Learning and neural Networks.

### Exercises

#### Mars Short Path Finding

- Finds the shortest energy consuming distance on Mar's elevated surface (image obtained from NASA).
- Uses Uniform Cost Search and Heuristic Search considering that the robot expends and gains depending if it is going up or down respectively.

<div class="gif-container">
  <img src="../assets/gif/marsShortestPath.webp" alt="Bouncing Head Game Demo" height="" width=""/>
</div>

#### Seduku Solver

The demo solves the [Hardest-Ever Seduku].

<div class="gif-container">
  <img src="../assets/gif/sedukuSolver.webp" alt="Bouncing Head Game Demo" height="" width=""/>
</div>

#### Self-driving Car

Car must not leave the road or hit junk on the road.

<div class="gif-container">
  <img src="../assets/gif/selfDrivingCar.webp" alt="Self Driving Car"/>
</div>

### Projects

#### Mice and Cats

There were 3 projects all based on pac-man inspired game of mouse, cheese and cats. The goal of all projects to implement the code driving the mouse to get all the cheese pieces to win the game. The difference was the AI model driving the mouse. The mouse was implemented using: Heuristic Search, Mini-Max Backtracking (with and without pruning) and Reinforcement Learning (Standard Q-learning and Feature based Q-Learning).

<div class="multiple-demo-container">
  <div class="demo-with-title">
    <img src="../assets/gif/miceAndCatsSearch.webp" height="300px" width="300px" alt="Mice and Cats Search"/>
    <div class="title">Heuristic Search</div>
  </div>
  <div class="demo-with-title">
    <img src="../assets/gif/miceAndCatsMinimax.webp" height="300px" width="300px" alt="Mice and Cats Minimax"/>
    <div class="title">MiniMax</div>
  </div>
  <div class="demo-with-title">
    <img src="../assets/gif/miceAndCatsRL.webp" height="300px" width="300px" alt="Mice and Cats RL"/>
    <div class="title">Reinforcement Learning</div>
  </div>  
</div>

#### Integer Image Classification

The project was to implement a Neural Network that classifies images of integers 0-9 trained on the [MNIST] data set.

Numbers learned by Neural Network:

<div class="gif-container">
  <video src="../assets/gif/mnistNeuralNet.webm" alt="MNIST Neural Net"/>
</div>

Classification rate:

```
Digit 0, correct classification rate=0.991853
Digit 1, correct classification rate=0.991364
Digit 2, correct classification rate=0.985477
Digit 3, correct classification rate=0.959538
Digit 4, correct classification rate=0.967880
Digit 5, correct classification rate=0.961456
Digit 6, correct classification rate=0.987654
Digit 7, correct classification rate=0.963947
Digit 8, correct classification rate=0.980080
Digit 9, correct classification rate=0.947917
Average correct classification rate: 0.973717
```

### Technology used

```
C
MatLab/Octave
```

[cscd84]: https://utsc.calendar.utoronto.ca/course/cscd84h3
[mnist]: http://yann.lecun.com/exdb/mnist/
[hardest-ever seduku]: https://abcnews.go.com/blogs/headlines/2012/06/can-you-solve-the-hardest-ever-sudoku
