build:
	@docker build -t myjenkins:1.0 .
run:
	@docker run  -p 8070:8080 -p 8071:8081 --name=jenkins-tuxmac -d -v /Users/jkelkar/.m2:/root/.m2 -v /Users/jkelkar/Workshop/local-docker-home/jenkins_home:/var/jenkins_home myjenkins:1.0
start:
	@docker start jenkins-tuxmac
stop:
	@docker stop jenkins-tuxmac
clean:	stop
	@docker rm -v jenkins-tuxmac
