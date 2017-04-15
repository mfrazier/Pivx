# pivx
Dockerized pivx master node

# Execution

docker -p 51472:51472 -v /host/pivx/dir:/home/pivx/.pivx --name pivx dok3r/pivx

docker exec -it pivx /bin/bash
