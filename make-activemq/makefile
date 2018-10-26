run:
	@docker run --name=activemq-tuxmac -p 8161:8161 -p 61616:61616 -p 61613:61613 -p 1883:1883 -d -v /Users/janardankelkar/Workshop/local-docker-home/activemq/data:/data -v /Users/janardankelkar/Workshop/local-docker-home/activemq/logs:/var/log/activemq -v /Users/janardankelkar/Workshop/local-docker-home/activemq/conf:/opt/activemq/conf webcenter/activemq:5.14.3
start:
	@docker start activemq-tuxmac
stop:
	@docker stop activemq-tuxmac
clean:	stop
	@docker rm -v activemq-tuxmac
