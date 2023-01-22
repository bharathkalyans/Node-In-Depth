<h3> Docker Commands</h3>

- docker pull {image-name}
- docker run {image-name}
- docker run -d {image-name} (detached mode)
- docker run -d -p{host-port}:{container-port} {image-name} (specify port)
- docker ps (gives all containers running!)
- docker ps -a (gives all containers running! and not running)
- docker logs {container-id}
- docker run -p6001:6749 --name redis-older redis:4.0 (naming a container)
- docker exec -it {container-id} /bin/bash
