# rearc_assign
Created an EC2 instance (t2.mdedium) on AWS using ubuntu 18.04
I install git, docker and default version jdk
I then intilised the git repo
I clone the repository (rearc quest) to my local environment.
I created a Dockerfile using some key modules.
I built a docker image from the dockerfile from where I ran it as a docker container (docker build -f Dockerfile -t quest .)
I attached the environment variable and secret to the container (docker run -d -p 3000:3000 -e SECRET_WORD=TwelveFactor quest:latest) 
