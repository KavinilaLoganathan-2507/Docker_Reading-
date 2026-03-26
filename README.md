# Docker_Reading

* Docker is a Containerization framework

* Isolated and secured 

* Image - Minimum set of files 

* Working with Docker:

* Creating a Docker file - a set of instructions, a base image, Application code, dependencies, environmental variables, and a set of comments (which makes the Docker run)

# docker build /<file_location>
# docker run [OPTIONS] IMAGE[:TAG|@DIGEST] [COMMAND][ARG..]

# DockerHub

Prebuilt images that can be downloaded and used 
1. Registry - has many images (languages)
   1.1 Public - open access (Docker hub)
   1.2 Private -  (Google and Azure)
2. Repository - Versions of the languages


Docker Desktop is a one-click-install application for your Mac, Linux, or Windows environment that lets you build, share, and run containerized applications and microservices.

It provides a straightforward GUI (Graphical User Interface) that lets you manage your containers, applications, and images directly from your machine.

Docker Desktop reduces the time spent on complex setups so you can focus on writing code. It takes care of port mappings, file system concerns, and other default settings, and is regularly updated with bug fixes and security updates.

Docker Desktop integrates with your preferred development tools and languages, and gives you access to a vast ecosystem of trusted images and templates via Docker Hub. This empowers teams to accelerate development, automate builds, enable CI/CD workflows, and collaborate securely through shared repositories.

# Install docker in desktop
<a href="https://docs.docker.com/desktop/setup/install/windows-install/">
Docker Desktop Installation Guide (Windows)
</a>

# Creating Docker file in real time in VS Code:

# File name rules:

**D** should be in uppercase

The file name should be **Dockerfile**

# CODE:

->start with **FROM** and **IMAGE**

->Search on Google and select the version 

->Creating working directory 

->copy files with **.** and move the files inside the container 

->**EXPOSE** with port number

->**CMD** running commands 

# Open Docker application :

->Can view items in two ways:

   -> Desktop (GUI)
   
   -> CLI
