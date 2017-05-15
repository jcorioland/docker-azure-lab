# Get started with Docker and Microsoft Azure

## Get a Microsoft Azure account

1. You have a Microsoft Azure pass ? Follow [this documentation](setup-azure.md).
2. You do not have a pass, then you can open a trial account [here](https://aka.ms/azure-trial).

## Create a simple VM with Docker installed

The simple way to create a Docker enabled virtual machine in Azure is to use Docker-Machine. 
Follow [this documentation](dockermachine-azure.md) to get started.

## Create a Swarm cluster in Azure

There are three was to create a Swarm cluster in Microsoft Azure:

1. Create multiple Docker-enabled virtual machine using Docker Machine (cf. documentation above), then follow [this documentation](https://docs.docker.com/engine/swarm/swarm-tutorial/create-swarm/) to create the Swarm cluster.
2. Use Docker for Azure CE following the documentation on [Docker website](https://docs.docker.com/docker-for-azure/)
3. Using Azure Container Service Engine, following [this documentation](https://github.com/Azure/acs-demos/blob/master/training/swarm/deploy-acs-engine.md). 

## Create an Azure Container Registry

If you need a private Docker registry up and running very quickly, a good solution could be to use the Azure Container Registry service which provide an implementation of the Docker open source registry, as a service, and fully compatible with the Docker CLI.

To create one, follow [this documentation](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-portal).