# Virtual Machine 💻

A virtual machine (VM)
is a virtual environment that functions as a virtual computer system with its own CPU, memory, network interface, and storage, created on a physical hardware system (located off- or on-premises). Software called a hypervisor separates the machine’s resources from the hardware and provisions them appropriately so they can be used by the VM.



# Docker 🦈

Docker is an open source containerization platform for building, deploying, and managing containerized applications. It enables to package applications into containers that encapsulate source code, libraries and dependencies required to run that code in any environment.

# Docker v/s virtual Machine

Virtual machine has its guest operating system above the host operating system, which makes virtual machines heavy. While on the other hand, Docker containers share the host operating system, and that is why they are lightweight.

The virtual machine does no share operating system, and there is strong isolation in the host kernel. Hence, they are more secure as compared to Containers. A container have a lot of security risks, and vulnerabilities as the containers have shared host kernel.

Docker containers are easily portable because they do not have separate operating systems. A container can be ported to a different OS, and it can start immediately. On the other hand, virtual machines have separate OS, so porting a virtual machine is difficult as compared to containers.

Containers are lightweight and can startup very fast compared to that of virtual machines,




# Containers


A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. Containers share the machine's OS system Kernel and therefore do not require an OS per application.

Container is just a process running from directory and all the data is coming from image.


# Why Docker?

1.Lightweight

2.Isolation

3.Scalability

4.Performance

5.Portability


# Docker Engine  

Docker Engine is an open source containerization technology for building and containerizing your applications. Docker Engine acts as a client-server application.



# Docker Architecture

Docker uses a client-server architecture. The Docker client talks to the Docker daemon, which does the heavy lifting of building, running, and distributing your Docker containers. The Docker client and daemon can run on the same system, or you can connect a Docker client to a remote Docker daemon. The Docker client and daemon communicate using a REST API, over UNIX sockets or a network interface.




# Docker Image

A Docker image is a file used to execute code in a Docker container. Docker images act as a set of instructions to build a Docker container, like a template. Docker images also act as the starting point when using Docker.




# Dockerfile Instructions

**FROM** - Take Base Image (Take from docker hub)

**LABELS** - Key value pairs, give project name or author name

**RUN** - Execute commands

**ADD/COPY** - Add files and folders into image

**ENTRYPOINT** - Allows you to configure a container that will run as an executable

**VOLUME** - Creates a mount point and marks it as holding externally mounted volumes

**EXPOSE** - Container listens on the specific network ports at runtime

**ENV** - To set an environmemt variable

**USER**- Sets the username

**WORKDIR** - Sets the working directory

**ARG** - Define a variables that user can pass at build time

