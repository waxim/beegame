# Bees In The Trap
Write a simple game in PHP using the following rules. You should use modern PHP styles and design principles. You can use symfony components but you should avoid using a fully prebuilt framework.

## Rules
- The game must be run from the command line. (Setup and installation commands such as `composer install` are fine)
- The game should have an executable shell file called `beesinthetrap`
- The game should be turn by turn
- A player should type `hit` to have their turn awaiting input after each previous turn.
- The game should show a message to the player after each turn, with the outcome of that turn. `e.g. Direct Hit. You took 12 hit points from a Drone bee`
- The game should be single player.
- The game should exit on game over, with a message informing the user of how many hits were needed to destroy the hive.
- The object of the game is to destroy a hive of bees.
- The hive has three types of bee
- The game is over when all bees are dead.

### Queen Bee
- The Queen Bee has a lifespan of 100 Hit Points.
- When the Queen Bee is hit, 8 Hit Points are deducted from her lifespan.
- If/When the Queen Bee has run out of Hit Points, All remaining alive Bees automatically run out of hit points.
- There is only 1 Queen Bee.

### Worker Bee
- Worker Bees have a lifespan of 75 Hit Points.
- When a Worker Bee is hit, 10 Hit Points are deducted from his lifespan.
- There are 5 Worker Bees.

### Drone Bee
- Drone Bees have a lifespan of 50 Hit Points.
- When a Drone Bee is hit, 12 Hit Points are deducted from his lifespan.
- There are 8 Drone Bees.

You should include tests.

You should submit your test as a PRIVATE repo on GitHub and add @waxim as a collaborator. 
