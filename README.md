# docker-wordpress-dev
docker-wordpress-dev

To use this docker-compose.yml file clone this repository and run "docker-compose up" from the repo directory.

If using docker-machine you will need to run "docker-machine ip default" to determine the IP address of the container as localhost will not work.

Once running you can view the application in browser at http://{docker-machine-ip}:8080

PHPMyAdmin has been included in this stack and can be accessed at http://{docker-machine-ip}:8181
