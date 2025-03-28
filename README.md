# Drone-Warfare-Simulator
Simulates the movement of multiple drones in a 3 dimensional space with constraints on range (Up to 15 units), speed (Up to 10), and enemy encounters (10 percent chance).
Drone movement is randomized and if movement goes beyond the allowed range it will be reset back to the origin (0,0,0). If an enemy is detected the drone will fire its weapon and return back to the origin.
The user specifies how many drones they want to deploy, the simulations runs for 20 iterations (time steps), and for each step, the current drone position and movement updates for each iteration are displayed.
