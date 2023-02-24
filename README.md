# Selenium grid with Docker 

This project represent how to run selenium grid with docker 

## pre-requisites 
Java 11 must be installed 
Docker must be installed 

### How to run selenium grid in docker
From terminal cd in to the repo and run below command 

`docker-compose -f docker-compose-v3-full-grid.yml up`


Go to localhost:4444 
after few minutes you can see the selenium grid is up and running 

### To stop the selenium grid server server
On same terminal press Ctrl + c and then 

`docker-compose -f docker-compose-v3-full-grid.yml down`

to remove all the docker images and containers 

`docker system prune -a`

and then press Y

### Warning if you have any other docker images or container that will also be removed by above command 
