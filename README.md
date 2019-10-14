# master-slave-jenkins

# Setup
1. Run `docker-compose up master` and copy the password from shell to Jenkins UI
2. Change the user/pass to u: jenkins p: jenkins
3. Run `docker-compose up worker`
4. If you need more than one worker you can scale it by `docker-compose scale worker=3`
