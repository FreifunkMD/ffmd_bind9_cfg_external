**ARCHIVED** Please apply changes to https://github.com/FreifunkMD/ffmd-bind9


# Bind9 zone config for ffmd

An image with this configuration is available at Docker Hub: https://cloud.docker.com/repository/docker/mrtux/bind9-ffmd/

Start as local DNS with:
```
docker run --rm -d -p 127.0.0.1:53:53/tcp -p 127.0.0.1:53:53/udp --name ffmd_dns mrtux/bind9-ffmd
```
