# cloud-config-server
We have multiple microservices. 
And for all the microservices there might be some few configurations that are repeated in all the microservices. 
It is not a good approach. So create a cloud config server in Git repository and save all the configurations there. 
Then create a config server which reads the git repo and it will give all the configurations to all microservices that are connected. 
