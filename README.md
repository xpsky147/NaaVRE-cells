# NaaVRE-cells

## Setup

After creating a new repository from this template, the docker registry must be configured by setting the following actions secrets and variables for repository:

- variable `REGISTRY_NAME` (eg. https://index.docker.io/v1/ for Docker Hub)
- secret `REGISTRY_PASSWORD`
- secret `REGISTRY_USERNAME`

To use ghcr.io with built-in authentication, `REGISTRY_NAME` should be unset.