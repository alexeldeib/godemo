# Go demo project

This is a simple project to demonstrate building three go binaries from the same repository.

The key insights is that Go executable must be defined as `package main` -- this is what tells Go to build a binary.

Try each of these:
```bash
# in root of repo, builds an executable named godemo
go build . 
# build client executable, output to current dir
go build ./cmd/client/client.go
# build server executable, output to current dir
go build ./cmd/server/server.go
```