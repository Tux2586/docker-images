build:
	@docker build -t mydataweave1:1.0 .
run:
	@docker run -it --rm -p8060:8080 --name=dataweave1-tuxmac -d mydataweave1:1.0
start:
	@docker start dataweave1-tuxmac
stop:
	@docker stop dataweave1-tuxmac
clean:	stop
	@docker rm -v dataweave1-tuxmac