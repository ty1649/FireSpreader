# FireSpreader
This is a forest fire simulation, complete with a user inputted amount of tree density (which I did as the percentage of the grid that's going to be filled with trees), and the trees are going to be spawned randomly on top of the grid. From here, my forest fire simulation spawns a fire at a random point in time, and then watches the fire spread to all neighboring trees who aren't on fire, and after a time step, the fire turns the tree to ashes, which repeats until the fire cannot spread anymore. (Run the GUI class for this)


This can test the probability of a fire burning everything with a monte carlo simululation as well, running this process 1000 times for each percentage value from 1-99. This can be used to determine the safety of where you lived based on the density of the trees/things that can spread fire, which can be used to benefit our community. (Run the MonteCarloOutput class for this).
