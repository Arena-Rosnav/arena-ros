# arena-ros
This repository contains the ARENA planner, a DRL-based approach for obstacle avoidance and environment navigation.   
Please note that a navigational policy is supplied for the following robot models only:
- Turtlebot3 Burger  

# Usage
## This planner can be chosen using the local_planner argument like so:
```bash
roslaunch arena_bringup start_arena.launch local_planner:=arena # Make sure that your virtual env/poetry is activated
```
## For more details regarding usage, please refer to our [documentation](https://arena-rosnav.readthedocs.io/en/latest/user_guides/usage/)

For more information have a look at the original [paper](https://arxiv.org/pdf/2104.03616.pdf)
