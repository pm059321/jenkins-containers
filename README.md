# Notes for build up docker-based Jenkins environment


build and start the jenkinse master and slave container

    docker-compose build
    docker-compose up

e.g. scale our amount on slave to `4`:

    docker-compose scale jenkinsslave=4

(use for updates) shutdown and remove all started jenkins containers
    
    docker-compose down

  
    

