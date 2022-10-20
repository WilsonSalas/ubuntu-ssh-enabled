# ubuntu-ssh-enabled
Ubuntu-ssh-enabled image
SSH Enabled Ubuntu Image for Test and Dev purposes ONLY!

Use:
Run the container:

docker run -d mmumshad/ubuntu-ssh-enabled

Identify the Internal IP

docker inspect <container-id-name>

SSH

ssh <container-ip>

Username: root

Password: Passw0rd

Based on : https://docs.docker.com/engine/examples/running_ssh_service/
