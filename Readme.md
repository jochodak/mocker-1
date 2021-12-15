# Mocker for application deployment

## 1. INTRODUCTION

*Mocker* is a software packaging platform that allows development teams to build, package, and deploy applications. A Mocker infrastructure only needs to run as many containers as needed. The customer only pays for the infrastructure that is being used at a given point in time. Mocker containers can run on any cloud infrastructure, but the mocker administrator tools are optimized for Amazon cloud services. 

## 2. MOCKER INFRASTRUCTURE

**Mockerfile** \
A text file defining the location of the resources needed by the Mocker container. Mockerfile defines Mocker Image.\
**Mocker Image**\
It is defined by the Mocker file and is used to create Mocker containers. It can be run in parallel in as many containers as necessary, depending on the cloud infrastructure under which it runs.\
**Mocker container**\
A bundle of software, libraries and configuration files. They are based on templates called images. When a container is created from a Mocker image, all the resources are bundled and run on a virtual machine dedicated exclusively to that Mocker container. Mocker containers can run on any cloud infrastructure

## 3. HOW TO DEPLOY AN APPLICATION
3.1 Microservices\
To deploy Mocker-based microservices install the Mocker daemon  that runs and orchestrates containers on a given software virtualization platform in the cloud\
3.1.1 Requirements
- Mockerfiles structure familiarity
- Mocker daemon API familiarity
- JavaScript knowledge
- Basic understanding of app containers (developers less familiar with app containers can start using the configuration templates provided by the Mocker foundation)

## 4. ADMINISTRATION TOOLS

 *Administration tools* are an additional solution for cost optimization. Customer pays for access to support and administrator tools. Administration tools are optimized for Amazon cloud services. \
With administration tools you can: 
- enable a rapid deployment of Mocker containers without the need of additional scripting on the customer’s side.
- have an access to the scripts to control the Mocker daemon and handle the initialization and shutdown of containers
- optimize cost of maintaining the infrastructure
- be offered an extensive documentation for developers in case you are not familiar with Amazon web services





