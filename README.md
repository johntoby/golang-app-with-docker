# golang-app-with-docker
This repository will consist of a Golang Calculator Application, with a Dockerfile to practice Multistage docker build

If I build this application the normal single stage dockerfile, the container size will be around 861mb. But using this Multistage docker build here, I have reduced the container image by almost 800% to just 1.9mb! 

You can pull the container and play around with it using 
```Bash
$ docker pull johntoby/simple-golang-calculator 
