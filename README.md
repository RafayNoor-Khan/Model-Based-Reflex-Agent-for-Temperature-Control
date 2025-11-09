This project implements a model-based reflex agent that controls room temperatures by turning a heater on or off depending on the desired temperature. The agent keeps track of previous actions in each room to avoid unnecessary toggling.

🔹 Features

Uses previous state memory to make decisions efficiently.

Controls multiple rooms independently.

Avoids redundant actions by checking if the heater is already on or off.

Easily configurable desired temperature.

✅ Key Concepts

Model-Based Reflex Agent: Uses both current percepts and an internal model of the world (previous actions) to make decisions.

State Memory: Keeps track of the last action for each room.

Decision Logic: Turns heater on if room is colder than desired, off if warmer or equal.

🔧 How to Run

Copy the Python code into a .py file or Jupyter Notebook.

Define your rooms and current temperatures.

Set the desired temperature.

Instantiate the agent and call act() for each room.
