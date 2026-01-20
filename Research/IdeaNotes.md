### Basic Functionality

- 'Admin process' gets status of the node(s) in the cluster
- Desired state is supplied with a config file (maybe in yaml)
- 'Admin process' checks to see if theres a difference in state
- If state is different fix it

### Code structure
In a deployment dir
- deploy.yaml - ansible playboook to deploy container
- autoswarmcfg.yaml - yaml file explaining to autoswarm how to deploy the services in deploy.yaml across the cluster and how to handle restarts and updates

then would run autoswarm . and it would deploy and manage what it needed to

### Languages?
- Python - same as ansible and with some intergration with docker
- C# - what im best at
- GO - something new
### This is just a fancy docker compose atm

### After that
- Look at scaling across a cluster
- Load balancing
- Overlay networks
- Autoscaling
- Cloud config