---
title: "Implementing Conway's Game of Life in Go"
date: 2023-06-06T16:40:21+05:30
draft: false
---

![Video Demo](https://i.imgur.com/22BVWt0.gif)

## Introduction

Hello everyone! In this devlog post, I want to share my journey of implementing Conway's Game of Life in Go. It was a fascinating project that allowed me to explore various aspects of Go programming and create a terminal-based rendering system. Along the way, I also developed a tick-based life cycle system and added the ability to customize window sizes. Let's dive into the details!

## Setting Up the Project

To get started, I created a new Go project and set up the necessary directory structure. I decided to keep the project simple and self-contained, so I didn't use any external libraries. This allowed me to have full control over the implementation and learn more about the language itself.

## Building the Grid

The first step was to represent the Game of Life grid. I created a Grid struct that consisted of a two-dimensional slice to hold the state of each cell. To make the grid customizable, I added parameters to specify the width and height during initialization. This way, users could create grids of different sizes based on their preferences.

## Rendering in the Terminal

Since I wanted a terminal-based rendering system, I utilized Go's fmt package to draw the grid on the terminal window. I looped through each cell of the grid and printed either a live cell or a dead cell representation based on its state. Additionally, I used ANSI escape codes to clear the screen and update the grid on each tick.

## Implementing the Life Cycle

Conway's Game of Life is known for its tick-based life cycle. I implemented a Tick function that calculated the next state of the grid based on the current state. Each cell's state depended on its neighbors according to the game's rules. After calculating the new state, I updated the grid accordingly. This process repeated on each tick, creating the illusion of movement and evolution in the game. The tick speed can be easily customized by manipulating the settings.


## Conclusion

Implementing Conway's Game of Life in Go was a rewarding experience. It allowed me to explore Go's features, such as slices, structs, and input handling. The terminal-based rendering system provided a simple yet effective way to visualize the game, while the tick-based life cycle system captured the essence of Conway's original concept. By adding customizable window sizes, I made the implementation more versatile.

I hope you found this devlog post insightful and inspiring. If you're interested in exploring the code, feel free to check out the [project repository](https://github.com/zubairmh/thelifegame) on GitHub. Thank you for reading, and happy coding!