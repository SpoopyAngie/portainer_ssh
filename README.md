# portainer_ssh
Simple bash script that creates a local Portainer (podman) container that connects to a external Docker socket using SSH

## Podman
A volume called `portainer-ce-data` will be needed. `podman volume create portainer-ce-data`
Enable Docker images by adding `unqualified-search-registries = ["docker.io"]` on `/etc/containers/registries.conf`
