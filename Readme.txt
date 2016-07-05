Code for steels Mars 

Functions and supporting functions used as follows: 

1.Setup function for setting up the environment

2.Reset to reset the environment

3.Paint-background, pick-rocks,see-obstacles, have-rock?, have-obstacles? for creating environment

4.land-spaceship for randomly selecting the position of the Fixed space shuttle

5.GO function for executing the entire code

6. RUN_AGENTS : A helper function to GO function to make easy understanding and kicking off the turtles movement

7.FOLLOW-RULES : Another helper function for managing the movement of turtles or agents

8. Wander : A function that makes turtles move randomly

9. Collect-rocks: The function that collects the rock samples from the cluster.

10. AVOID-OBSTACLES : This function makes sure the agent avoid the obstacles present in the environment

11.HEAD-TO-SPACESHIP : Once the rock samples are collected, this function makes sure the agents reach the spaceship and then back to rock clusters

12. FOLLOW-CRUMBS : Makes use of diffused crumbs from the radioactive-crumbs to follow the path Up-gradient or uphill

13. Reporting function that reports an intermediate value for an expression required for following the trail of crumbs

14. Finally, I made use of several global or user input variables to vary rock-density; obstacle-density; Number of agents; diffusion-rate of the rock samples; decay-rate of the radioactive crumbs.