# PredatorPrey

## Installation
Before using the program, install the latest version of Netlogo [here](https://ccl.northwestern.edu/netlogo/).

## About
A simple predator prey model that uses foxes and rabbits as the agents. The environment in which the agents roam are within a 30 by 30 grid in which the green patches symbolizes the grass and the black patches are marked as eaten grass. The rabbits survive by eating the grass, while the foxes survive by eating the rabbits. The table below contains the initial population of both agents.

| Agents	  | Population  |
| ----------- | ----------- |
| `Foxes` 	  | 50			|
| `Rabbits`   | 50			|

The rabbits will starve to death after `10` ticks if they cannot find grass to eat. They eat if they are standing on a green patch. If a grass patch is eaten, then the patch will turn black and will regrow after 100 ticks have passed. The foxes will starve to death after `50` ticks if they find no rabbits to eat. They eat any rabbits that are on the same space as they are. Both agents will have a `1/50` chance to create a new offspring, have random movements, and have a turn and forward radius of `50`.

## Usage
If using the "PredatorPrey" program: Click on `Setup` to generate the environment and agents. Press `Go` to start the program and it will stop at 500 ticks. To run the program indefinitely, press `Go 🔁`. The sliders can be used to modify the configurations of the program.

If using the "PredatorPrey(Scenario4)" program: Similar to "PredatorPrey" however with slightly different configuration.

In the model view, there is also a plot screen where the populations of both foxes and rabbits are plotted on a line graph to show the changes in population over time.

## Authors
- Caoile, Sean
- Lim, Aurelius
- Tan, Gavin
- Yongco, Denzel

## Image
<img src="predatorprey.png">
