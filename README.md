# Continuous Integration by Jenkins

### Test the project locally by Docker Compose
 

### Frok this repo

Fork the repository by clicking the "Fork" button on the top right corner of this page. This will create a copy of the repository under your GitHub account.

### Clon this repo

Clone the forked repository to your local machine using the following command:

```
git clone https://github.com/<your-username>/Demo-DevOps_project.git
```

change the working directory to the cloned repo to Test the project locally by Docker Compose 

```
cd Demo-DevOps_project
git checkout jenkins_CI
docker-compose -d up 
```
and you can check this link 
`http://localhost:9090/healthcheck`

![docker-compose](https://github.com/Mohmed3del/Demo-DevOps-project/blob/main/screenshots/docker-compose.png)
