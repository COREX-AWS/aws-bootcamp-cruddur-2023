# Week 1 — App Containerization

# Security on Container

This week the team will be talking about docker containers and the best practice. I will write the 10 best practices that you need to know.
# What is container Security?

Container Security is the practice of protecting your application hosted on compute service like containers.
# Why container is popular?

It is a angnostic way to run application. Most people started developing apps on container due to the simplicity to pass the package without considering requirements.

# Managed Vs Unmanaged Container

Managed Containers means that the Provider (AWS) managed the underlying service for the container (ECS or EKS). In this case Cloud provider will be managing the security prospective .

Unmanaged Containers means you are running your container on your servers and you have to manage all the system (for example you will be in charged to apply security patches).

# Difference between RUN and CMD

RUN is a command we run to create a layer in the image / CMD is a command that the container is going to run when it starts up