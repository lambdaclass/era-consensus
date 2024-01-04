# Running a node

1. Create a `.txt` file in the root of tools crate, containing the addresses of where the node will run, in the format `IP:PORT` each address has to be a separate line.
2. Do `make node-configs`. This will create a directory called `node-configs` with one folder per address in the `.txt` file with the necessary config files for the node.
3. Execute `make run-node IP=<NODE_IP>` the default value for this command would be `127.0.0.1:8000`. Note that this command will take control of the terminal.
