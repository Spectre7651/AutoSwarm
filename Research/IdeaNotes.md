### Basic Functionality

- Checks to see if manager node is up
- Managers work by first in priciple ie 1st one started is the manager and the others are 2/3/4 etc
- When a manager they check to see if a node with a lower management id is active = stop controlling cluster if one is present
- If manager - run ansible scripts to make cluster scale correctly
- use placement groups for parallel services
- use overlay network with load balancing - same as swarm