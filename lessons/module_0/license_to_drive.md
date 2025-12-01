---
index: 2
module: module_1
task: license_to_drive
previous: test_drive
next: short_distance_race
---

# Lesson 2. License to drive

## Objective

Control the duration of the robot's movement by modifying parameters.

## Introduction

In this lesson, we are granting you the driver's license. Today, you will be writing the program on your own without the instructor's help. However, first, let's look at how we control the robot's distance.

## Theory

Think back to the previous lesson. You used this line of code:

`robot.move_forward_seconds(3)`

**What do you think the number `3` did?**

If you guessed that it told the robot to move for **3 seconds**, you are correct!

In programming, this number is called a **parameter**. Parameters allow us to pass specific instructions into a command.
* If you change the parameter to `1`, the robot drives for a short time.
* If you change the parameter to `10`, the robot drives for a long time.

You don't need to rewrite the whole code to change the distance; you only need to change that one number.

## Assignment

Write a program for the robot to make it drive straight for **5 seconds**.

1.  Import the library as (`from lineRobot import Robot`).
2.  Initialize the robot (`robot = Robot()`).
3.  Call the move function with the parameter set to 5.
4.  Click **Verify** to upload your code.

## Conclusion

Congratulations! You have successfully modified a parameter to control your robot. You now understand that by changing a single number, you can significantly change the outcome of your program. In the next lesson, we will explore the robot's movement in different directions.
