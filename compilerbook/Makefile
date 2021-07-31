test:
	hostname
	whoami
docker-image:
	docker build -t compilerbook .
docker-test:
	docker run --rm -v /Users/hiro/dev/github/mycompiler/compilerbook:/compilerbook -w /compilerbook compilerbook make test
docker-clean:
	docker rmi compilerbook
