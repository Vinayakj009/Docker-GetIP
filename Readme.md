This plugin adds the "getip" command to docker so that you can quickly get the ip addresses of your running containers.
The plugin throws an error if there are no running containers.

# Prerequisites
- Docker version 19.03 or higher.
- Bash
- Experimental mode enabled in docker.

To enable the experimental mode in docker, simple add the "experimental":"enable" to the `~/.docker/config.json` file.
If the file does not already exist, then create one.

# Installation
To install the plugin run `install.sh` shell script.

# Testing
Make sure you have at the least one container running.
Then run the command `docker getip`.
This will print the name of the container followed by the ip addresses linked to the contianer followed by the container id.
