# How to get this thing deployed on a fresh server

1. Install docker on the server, start docker daemon (https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-centos-7)
2. Make sure that docker daemon is running!!!
3. Install docker-compose on the server (https://docs.docker.com/compose/install/#install-compose)
4. Make a directory for the project
5. In new directory, make a file called `docker-compose.yml`
6. Grab the latest version of the `docker-compose.yml` file from this git repo, and paste the contents into the server's new `docker-compose.yml` file
7. Run the following: `sudo docker-compose up`
