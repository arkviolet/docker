# docker

## docker-build

```bash
sudo docker build -t kviolet:latest .
```
## docker user
```bash
sudo usermod -aG docker $USER
newgrp docker
```

## docker-run

```bash
docker-compose -f kviolet.yaml run --rm dev

# export http_proxy=http://172.29.48.1:10809
# export https_proxy=http://172.29.48.1:10809
```
## docker_platformer
