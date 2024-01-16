[# Kubernetes
CKA Exam Preparation and Links](https://synopsys-my.sharepoint.com/:f:/p/anmolm/EtNw7gu2p1dKogGSvgLgwusBDB9jd5pfEXaoEuJ0pf12jQ?e=lwPrtp

Docker

Important Commands

	• List running containers - docker ps
		○ List all containers - docker ps -a
		○ Newer versions also has - docker container ls
	• docker images - list docker images

	• Start container - docker start <container id or container name>
	• Stop container - docker stop <container id or container name>
	• Delete container - docker rm <container id | container name>


Running Docker Hello World
	
	• Test Hello World
		○ docker pull hello-world
		○ docker run -it hello-world
		
	• Create a local Hello World
		○ Create a Dockerfile with below content :
			FROM ubuntu:18.04
RUN echo 'Hello, World!' > /test.txt
		○ docker build -t hello-world .
		○ docker run hello-world

Create Docker Volume
	• docker volume create <data_volume>
docker run -v data_volume:/var/lib/mysql mysql)https://synopsys-my.sharepoint.com/:f:/p/anmolm/EtNw7gu2p1dKogGSvgLgwusBDB9jd5pfEXaoEuJ0pf12jQ?e=lwPrtp

Docker

Important Commands

	• List running containers - docker ps
		○ List all containers - docker ps -a
		○ Newer versions also has - docker container ls
	• docker images - list docker images

	• Start container - docker start <container id or container name>
	• Stop container - docker stop <container id or container name>
	• Delete container - docker rm <container id | container name>


Running Docker Hello World
	
	• Test Hello World
		○ docker pull hello-world
		○ docker run -it hello-world
		
	• Create a local Hello World
		○ Create a Dockerfile with below content :
			FROM ubuntu:18.04
RUN echo 'Hello, World!' > /test.txt
		○ docker build -t hello-world .
		○ docker run hello-world

Create Docker Volume
	• docker volume create <data_volume>
docker run -v data_volume:/var/lib/mysql mysql![image](https://github.com/anmolmore/Kubernetes/assets/1755881/e962e6cf-8461-4c5b-94bb-aea4fa662459)

