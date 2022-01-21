# Differences in MacOS & Linux command

1. echo

# Useful commands

1. Git related
* use history command:
~~~~
history
! + number of the past command
~~~~
2. crtl+A: start of a command, crtl+E: end of a command
3. clear all __pycache__ in current directory:
~~~~
find . -name '__pycache__' -type d -exec rm -rf {} \;
~~~~

4. clear all .pyc file in current directory:
~~~~
find . -name "*.pyc"  | xargs rm -f
~~~~
5. Docker related:
* inspect container ip address:
~~~~
docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' container_name_or_id
~~~~
* clear all the images and containers in current machine
    * Stop the container(s) using the following command:
    ~~~~
    docker-compose down
    ~~~~~
    * Delete all containers using the following command:
    ~~~~
    docker rm -f $(docker ps -a -q)
    ~~~~
    * Delete all volumes using the following command:
    ~~~~
    docker volume rm $(docker volume ls -q)
    ~~~~
    * Restart the containers using the following command:
    ~~~~
    docker-compose up -d
    ~~~~
