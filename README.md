# testing-podman
showing some weirdness in podman

1. git clone https://github.com/whitel/testing-podman.git
1. sudo podman build -t my/apache .
1. podman images
```bash
 sudo podman images
REPOSITORY                 TAG      IMAGE ID       CREATED          SIZE
docker.io/library/fedora   latest   9110ae7f579f   6 weeks ago      246MB
docker.io/my/apache        latest   f6cc2584f873   32 seconds ago   448MB
```

why is this tagged docker.io?


