

TAG := $(shell basename $$PWD)


all: build

build:
	TAG=$(TAG) docker-compose build
	TAG=$(TAG) docker-compose --file docker-compose.lotan.yml build 