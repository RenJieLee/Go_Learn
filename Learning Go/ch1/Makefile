.DEFAULT_GOAL := build

fmt:
		go fmt ./...
.PHONY:fmt

lint: fmt
		golint ./...
.PHONY:lint

vet: fmt
		go vet ./...
.PHONY:lintgo

build: fmt
		go build hello.go
.PHONY:build