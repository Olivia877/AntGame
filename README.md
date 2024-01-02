# AntGame
Game Overview:
This is a simulation game implemented in Java, emulating the behavior of ants through the use of finite state machines.
In this game, ants aim to collect food and transport it back to their home, the ant hill, triggering the addition of another ant to the colony. Subsequently, ants become thirsty after successfully bringing food to the ant hill. They then venture out to find water, quench their thirst, and resume the cycle by searching for more food. During their quest, ants move randomly when collecting food and water, employing the A* algorithm to take the shortest path home when carrying food. Additionally, ants must navigate around randomly placed poison while safely traversing terrain, water, and food.

Instructions for Use:
The user has the responsibility of placing the ant hill and selecting the initial number of ants.
The ant hill is positioned by clicking on an empty tile on the game board. Each click on the ant hill adds one more ant to the starting size of the ant colony. After placing the ant hill and configuring the desired number of ants, pressing the "Execute" button initiates the simulation by randomizing the board setup.
Two buttons are provided:
"Blank": Halts the simulation, enabling the user to set up a new scenario.
"Execute": Commences the simulation.

Compilation:
Compilation: javac Ant.java AStar.java Board.java Connection.java FiniteStateMachine.java Game.java Graph.java Heuristic.java Node.java NodeRecord.java State.java Transition.java
Execution: java Game (command line) or FSM.jar executable included in submission
