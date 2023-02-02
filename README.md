# battlesnake_minimal


This may help you get started with your RL battlesnake. Take it, copy, paste, modify, rewrite, refactor.

A suggestion is to change the <code>game_engine.step()</code> from outputting a string to continue the game, to outputting a (state, action, reward) tuple or whatever you need for your type of RL agent.
The game continuation can be converted to a property. That is, <code>game_engine['complete'] = 'running'</code> updated to <code>game_engine['complete'] = 'complete'</code> when finished, and the <code>while loop</code> looks for that instead.

Some of the logic may not be quite right, specifically the fine details about how deaths are resolved.


Features:<br>
- Easily save games<br>
- Visualization of games<br>
- Can start from an arbitrary game state (may be interesting in testing how different snakes make decisions for a given board state)<br>
- A simplesnake class to build from and battle against. Only needs a name and <code>move()</code>.
