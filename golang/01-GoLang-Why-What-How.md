## Why Should I learn GoLang?

Recently I've been thinking to learn a programming language. Since there is no direct business need; choices are totally upto me. Which one should I pick?
I've affinity for Databases, Messaging, recent addition of cloud infrastructures. But above all I love production systems.
It is important to undertand how system (mis)behaves in production. Without understanding how it is written; it gets little difficult.
Lot of technologies like Docker, Kubernetes, Linkerd, rclone, MinIo, Terraform, Traefik, Coackroachdb, etc are written in GoLang.
Given that some are typical production candidates; I decided to learn GoLang.

## What should I learn?
It is hard to define what you want to learn about a Language without beginning. But I thought its fun to set some end goal and work towards that. Based on how much affinity I develop; this excercise may probably be a futile attempt.

So I want to learn the basics like data structures; functions; conditionals, dependency injection, concurrency. As a prototype, I want to create a (Micro)Service.


## How to start?

So how should I begin? Project documentation, a book, a Udemy Course or somewhere else?
I found this repository of useful learning resources. TDD for learning a language. I like the idea. https://github.com/quii/learn-go-with-tests

## Getting Started

### Install Go on Windows

* Install using EXE file
* Set GOPATH=/c/dev/repos/goworkspace
* go get github.com/nu7hatch/gouuid
* Check if the package is pulled in workspace

### Common Commands

Check Go Environment Variables

```
go env
```

Two most important configurations are

```
GOROOT=C:\dev\tools\Go
GOPATH=C:\dev\repos\goworkspace
```

```
# Executes the Go program
go run hello.go
# Executes test cases
go test
# Creates an EXE file. 
# Strange that even when test case fails; build is OK
go build
# Installs the binary in bin folder
go install
```
