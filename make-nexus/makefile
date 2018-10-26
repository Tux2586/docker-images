build:
	@docker build --rm --tag sonatype/nexus .
run:
	@docker run -d -p 8079:8081 --name nexus-tuxmac -v /Users/janardankelkar/Workshop/local-docker-home/nexus_home/data:/nexus-data  sonatype/nexus:latest
start:
	@docker start nexus-tuxmac
stop:
	@docker stop nexus-tuxmac
clean:	stop
	@docker rm -v nexus-tuxmac
