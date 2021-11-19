


.PHONY: start
start: compose
	open http://localhost:8000

.PHONY: compose
compose:
	docker-compose up -d

.PHONY: down
down: 
	docker-compose down

.PHONY: rmv
rmv: 
	docker-compose down --volumes r

.PHONY: exe
exe:
	docker exec -i -t wordpress_docker_wordpress_1 /bin/bash

.PHONY: wget
wget: start
	wget -p -k http://localhost:8000

.PHONY: httrack
httrack: start
	@ cd .. ; \
	httrack --ext-depth=1 http://localhost:8000 ; 