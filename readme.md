:whale:

##  POSS DEMO: Environment LAMP + Overlay Network Docker

### PREREQUISITES  
   - docker >= 1.9
   - docker-compose >= 1.5.0
   - swarm >= 1.0

### 1 : You must create a Docker Cluster like described in :
   - https://github.com/herveleclerc/poss-demo-libnetwork  

### 2 : Adjust Environment variables in   
  - compose/00-setenv.sh  
  - compose/*.env if needed  

### 3 : docker-compose.yml 
  - docker-compose-link.yml : Wordpress will run on a single host with link between container
  - docker-compose-net.yml : Wordpress on a multi host based on overlay network
  - docker-compose-net-vol.yml : Wordpress on  multi host based on overlay network and volume driver


