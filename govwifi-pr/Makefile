DOCKER_COMPOSE = docker-compose -f docker-compose.yml

ifdef ON_CONCOURSE
  DOCKER_COMPOSE += -f docker-compose.concourse.yml
endif

DOCKER_BUILD_CMD = $(DOCKER_COMPOSE) build

build:
ifndef ON_CONCOURSE
	$(DOCKER_BUILD_CMD)
endif

prebuild:
	$(DOCKER_BUILD_CMD)
	$(DOCKER_COMPOSE) up --no-start
