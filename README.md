# pivx

Dockerized pivx

# Examples

Start the container:

    docker -p 51472:51472 -v /host/pivx/dir:/home/pivx/.pivx --name pivx klexx/pivx
    
Access shell / bash:

    docker exec -it pivx /bin/bash
