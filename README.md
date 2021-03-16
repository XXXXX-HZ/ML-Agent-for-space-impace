# ML-Agent-for-space-impace

**Set-up**: Space Impact is a shoot 'em up game and the Agent has the ability to freely move horizontally and vertically but cannot increase the speed of the screen's auto-scrolling feature.  

**Goal**: The agent must kill the final boss and reach the final line while avoiding the obstacles(Enemies and Bullets).


**Agent Reward Function**:

+ 0.01 for every time kill an enemy
+ 0.01 for every time agent’s bullet hits the boss
- 0.2 if the agent hit an obstacle(lose one life)
+ 0.1 if the agent pick up a healthUp( add one life) 
- 1.0 if the agent die (episode ends)
+ 1.0 if the agent arrive to the final position(episode ends)

**Behavior Parameters**:
Actions: 3 discrete action branches
Forward Motion:(3 possible actions: Forward, Backwards, No Action)
Side Motion (3 possible actions: Left, Right, No Action)
Shoot (2 possible actions: shoot, No Action)

**Demo Video**
https://youtu.be/FVzCjiUpnNQ
