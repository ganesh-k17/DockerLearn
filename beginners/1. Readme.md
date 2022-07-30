# Docker Basics

## Objectives

* What are Containers?
* What is Docker?
* Why do we need it?
* What can it do?

--------------------

* Run Docker Containers
* Create a Docker Image
* Networks in Docker
* Docker Compose

## Docker! Why we need it

To Avoid:

* Compatibility/Dependency
* Long setup time
* Different Dev/Test/Prod Environments

## What can do with it

We are able to run each  component in a separate container with it's own dependencies and its own libraries all on the same VM and the OS but within environments or containers, which had to build the docker configuration once and all our developers can start with single docker run command irrespective of what the underlying OS they are running on, all they needed to do is to make sure they installed docker in their machine.

## What are containers

Containers are completely isolated environments as in, they can have their own processes or services, their own network interfaces, their own mounds but they all share the same OS kernel.

## Public docker repository

These are the places where organizations stores their created docker images and they pull them whenever they needed.

## docker image

Docker images are Package Template Plan which is used to create container we can mean it as the template has configurations (Docker File is used to create docker image.) needed to create container.

## Containers

Containers are running instances of images isolated on their own environments.
