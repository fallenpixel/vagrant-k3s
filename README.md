# Vagrant k3s

Uses vagrant and an ansible playbook to automatically provision and install k3s.

## Using:

- Ensure that the node-token is _NOT_ currently in the data directory. If it is, remove the data folder.
- `vagrant up`
- `vagrant ssh` to reach the server, or `vagrant ssh k3sagent` to reach the agent.
