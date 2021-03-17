# jenkins
CI/CD pipeline

#### Step for system setup
- Install Docker

  [Install and download docker](https://docs.docker.com/docker-for-windows/install/ "Docker Documentation")
- Check docker version

  `docker version`
  
- Run jenkins in Docker

`docker run --name my-jenkins-1 -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts`
- Navigate to [localhost:8080](http://localhost:8080)
- Unlock jenkins using admin password from terminal
- Install suggested plugin
- Reinstall if fail (skip if only few are failed)
- Create first admin user
- Configure instance by saving jenkins url `http://localhost:8080/`
- Restart and use

## Local jenkins set up is completed
 
