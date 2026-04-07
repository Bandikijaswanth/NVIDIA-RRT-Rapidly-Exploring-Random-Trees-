# NVIDIA-RRT-Rapidly-Exploring-Random-Trees-
AIM

To verify goal connection in RRT by checking whether a sampled node lies within the goal radius.

PROCEDURE
Initialize the distance of the sampled node from the goal
Define the goal radius
Compare the node distance with the goal radius
If distance ≤ goal radius, connect to goal
Otherwise, continue exploration
Display the result
CODE
# Distance of sampled node from goal
distance = 0.3   # in meters

# Goal radius
goal_radius = 0.4

# RRT goal connection check
if distance <= goal_radius:
    result = "Goal Connected"
else:
    result = "Not Connected"

# Output
print(result)
OUTPUT

Goal Connected

RESULT

The sampled node lies within the goal radius, so the goal is successfully connected in the RRT algorithm.
