# Notes_crt_do188
Notes_crt_do180 

# Network

podman network create network-01

podman run -d --name new-container --net network-01 container-image:latest


´´´Containerfile
FROM registry.access.redhat.com/ubi9/nginx-120:1-39
RUN echo "It is pitch black. \
You are likely to be eaten by a grue." >> index.html
CMD nginx -g "daemon off;"
´´´
