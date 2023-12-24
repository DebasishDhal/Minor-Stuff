I started Leetcode in 2023. I want to have a track of how my rank changes with the course of time. 

Leetcode provides a rank vs time graph, but I wanted to make something myself.

The end-to-end thing contains three components

- A python script that will fetch the rank from LeetCode website.
- A batch script that will run the script within proper Python environment, since web scrapping libraries like bs4 do not come pre-installed with Python.
- Task Scheduler
  - Create ```Basic Task```, give a name to it. Choose its frequency in trigger section.
  - Choose ```_start a program_``` in Actions.
  - In Program/Script, provide path to the bat file. Also put ```"C:/"``` in the ```Start in (Optional)```. Even though it says optional, it's actually mandatory.
  - Finish

***********************************************

<p align='center'>
  <img src = "images/rank_graph.png">
</p>
