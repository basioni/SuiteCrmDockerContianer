# SuiteCrmDockerContianer
A SuiteCRM Container for local development and based on Betnami Containers.

# Installation 
1. clone the repo to your local machine.
```
gh repo clone basioni/SuiteCrmDockerContianer
```
3. Create 2 folders as local volumes for containers:
```
sudo mkdir mariadb_data
sudo mkdir suitecrm_data
```
3. Make sure the folders have the right access permissions:
```
sudo chmod -R 777 "mariadb_data"
sudo chmod -R 777 "suitecrm_data"
```

4. Run the container using docker-compose:
```
sudo docker compose up -d 
```
5. To stop the container run:
```
sudo docker compose down
```
