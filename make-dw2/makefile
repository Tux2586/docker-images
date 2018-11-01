build:
	@docker build -t mydataweave2:1.0 .
run:
	@docker run  -p 8062:8080 --name=dataweave2-tuxmac -d mydataweave2:1.0
start:
	@docker start dataweave2-tuxmac
stop:
	@docker stop dataweave2-tuxmac
clean:	stop
	@docker rm -v dataweave2-tuxmac