# COGS 300 Project
## EVE by Team 6 
#### (Jacky Fu, Reilen Millar, Disha Pandurangi, Sarahi Zuniga Ruiz)
EVE was made for the COGS 300 Lab Project. The goal of our project was to make a robot to take part in a 2-player game which focussed on collecting the maximum number of balls possible. 
Our strategy for the robot EVE focuses on efficiently managing defense and collecting balls in small quantities. Our robot receives a higher reward for carrying a smaller number of balls at once (1-2 getting the highest reward, while greater numbers get a smaller reward) and having many balls in its base. It also has negative rewards for dropping balls and having no balls in its base. 
Since our strategy is currently based mainly on defense, some other potential implementations to ensure a balance for offensive skills of the robot might be encouraging the robot to steal balls from the other robot if it has more balls in the opposing base and there are no fair balls. We can implement a helper to assign rewards for this. Using these rewards and adjusting as needed, we train the robot using the demo that has the highest reward out of all our trials and the GAIL ML configuration to ensure optimal training. 
The script for EVE's strategy can be found in EVE.cs 
Currently, the repository is missing folders so it cannot be loaded in Unity as a complete project. Will be uploaded soon.
