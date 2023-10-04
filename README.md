# Artemis Supplier implementation
---
## Requirements
* Docker
* Docker-compose plug-in
* Python3

**NOTE BEFORE BUILD:** You must add the following files given by the Artemis provider:
1. The `config.env` file to `configuration/` folder
2. The `swarm.key` file to `ipfs/` folder

## Build
Run the command:
<code>docker-compose build</code>

## Start containers
Run the command:
<code>docker-compose up -d</code>

**NOTE:** To initialize ScyllaDB tables run:
1. <code>pip install scylla-driver</code>
2. <code>python initScyllaTables.py</code>