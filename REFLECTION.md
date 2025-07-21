# Reflection – Daily Schedule Simulator

## What was your approach to designing the schedule?
I wanted the schedule to match my most productive morning when I wake up with time to work out before starting my day.

## What was one challenge or unexpected behavior you encountered?
At first I thought I could make all the times in setTimeout the same value (5000ms) for testing, but I realized that they don’t run back to back and the times needed to be cumulative.
If I wanted to test the script and have them all 5 seconds apart, I needed each setTimeout value to be 5000 more than the previous one.
Once I did this everything appeared in the correct order.

## What does this assignment teach you about async code?
This showed me that code can wait to be run at a later time (as given by the value at the end of setTimeout) and the page will update when the timer is ready.

## What creative element did you add?
I added personalized emojis to each activity.

## How does this project simulate or differ from real-world schedules?
It is similar to real-world activities in that the order they are in is the appropriate order they would happen in real life.
They differ in that in the real world the timings may be different day to day and have some variance, and that some days I may not have the motivation to work out and might sleep in instead.