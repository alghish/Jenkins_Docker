# Jenkins command Running

> docker run --security-opt seccomp=unconfined -p 8080:8080 -p 50000:50000 -d -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts

## Run

In terminal just run prevoius command and if you want check log you can using below command

> docker log [container_id]

## Notes

In command added `--security-opt` because will appear error while running command
