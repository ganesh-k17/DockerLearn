# Install docker in linux machine

To check the version of my linux machine

> cat /etc/*release*

To remove docker in an existing machine

> sudo apt-get remove docker docker-engine docker.io containerd runc 

Download get-docker.sh this will automate the docker installation

> curl -fsSL https://get.docker.com -o get-docker.sh
cat /etc/*release*

Run downloaded file

> sudo sh get-docker.sh

To Check the version

> sudo docker -v

To check whether docker is properly installed.

> sudo docker run docker/whalesay cowsay Hello-World!

To start docker service if docker daemon is not running or getting any issue running above commands.

> sudo service docker start