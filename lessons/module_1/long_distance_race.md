---
index: 5
module: module_1
task: long_distance_race
previous: maneuvering
next: draw
---

# Lesson 2.3 Long distance race

## Objective

Write a program to make the robot drive a specific path.

## Introduction

Now that you can move the robot in all four directions, it is time to combine these moves. In this lesson, you will write a code to guide the robot along a specific path.

## Theory

In previous lessons, you wrote code to make the robot move. Let's define what a **program** actually is.

A program is simply a list of instructions. The robot reads your code from top to bottom, one line at a time. It finishes the first movement completely before starting the next one.

## Assignment

Write a program for the robot to follow the route shown in the image below.

![trajectory](https://github.com/autolab-fi/hamk-demo-course/blob/main/images/module-1/trajectory.png?raw=true)

**Cheat Sheet: Functions you know**

Here are the commands you can use to build your program:

* `robot.move_forward_distance(distance)`
* `robot.turn_right()`

*Remember: Replace `distance` with a number (e.g., 20 or 30).*

## Conclusion

Great job! You now understand how to chain commands together to create a full program. In the next lesson, we will learn how to control the robot's speed.
