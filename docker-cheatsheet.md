# Docker Cheatsheet

| Command | Description |
| - | - |
| docker system prune -af --volumes | Remove all |
| docker image rm -f $(docker image ls -q) | Remove all images |
| docker container rm -f $(docker container ls -q) | Remove all containers |
| docker volume rm -f $(docker volume ls -q) | Remove all volumes |
