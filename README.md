# Jenkins With Docker
This uses the latest LTS version of Jenkins and installs docker in that container. The reason for this was to be able to run docker commands in the containerized Jenkins UI.

## Usage

### Build

### Deploy


## References
[~jpetazzo/Using Docker-in-Docker for your CI or testing environment? Think twice](http://jpetazzo.github.io/2015/09/03/do-not-use-docker-in-docker-for-ci/) - This was the first useful link that guided me to the idea of running docker commands in Jenkins

[Docker in Docker?](https://itnext.io/docker-in-docker-521958d34efd) - This was same as above but newer, which re-enforced that I was going in the right direction

[The simple way to run Docker-in-Docker for CI](https://getintodevops.com/blog/the-simple-way-to-run-docker-in-docker-for-ci) - This was what really cleared it up. I used the Dockerfile from the repository https://github.com/getintodevops/jenkins-withdocker. I made some modifications
