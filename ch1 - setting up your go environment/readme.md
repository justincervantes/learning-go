# Setup

1. `go mod init hello-world`
2. `go build or go build -o hello` (named exe)
3. run the exe `./hello-world.exe`
4. `go fmt ./...` (apply the fmt command to all thje files in the current dir and subdir)
5. write your Makefile to automate the build process (requires choco install make on windows machines, though is natively support in unix environments)

# Notes about Makefile

- default goal is what the command `make` will try to run up until
- if you don't use dependencies, if you set the target to clean, it will just clean... if you want it to run then clean, set the goal to clean, and make clean dependent on run.
