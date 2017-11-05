# opsschool-ci-cd-lesson

Welcome to our CI/CD session.
Here you will have instructions on how to create the Jenkins environment.
And the code you will have to deploy.

* Step one:
On your VM, with docker installed, build Jenkins:
```
docker run -d --name opssjenkins -p 8080:8080 -p 50000:50000 -v /home/ubuntu/jenkins_pers:/var/jenkins_home jenkins
```

* Step two:
Also on same VM, install a docker slave, as RUBY.
