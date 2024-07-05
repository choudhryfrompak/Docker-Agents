# BUILD THE AGENT  

First of all you need to install docker.  
you can use this [Guide to install docker](https://docs.docker.com/engine/install/) to install docker on your computer.  

Once you have installed Docker on your computer, you can either pull the agent directly from DockerHub by running this command.  

`docker pull choudhry2272/dataset-agent:latest`  
and  
`docker run -it -v <path to dataset directory>:/app/data choudhry2272/dataset-agent`  

OR if you want to recreate the setup i have shown in the video, then you can clone this repository  

Run:  
`git clone https://github.com/choudhryfrompak/Docker-Agents.git`  

Then change you directory to docker-agents folder and run the following commands there:  
`docker build -t <name of the image> .`  

This command will build image of the agent.  
`docker run -it -v <path to dataset directory>:/app/data <name of the image>`  

This will run the agent and then you can proceed with the prompts shown.
