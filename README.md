# Imp Commands and Details
1) Command > go env -w GOSUMDB='sum.golang.org' 
to solve GOSUMDB invalid or other issue or initializing any env variable
2) Command > go env
to check, ENV variable of go
3) COmmand > go mod tidy -e
to clean the go library
4) Command > go clean -modcache
to clear module cache
5) Command > go mod verify
to verify module variable
6) Command > go list all
to list all modules
7) Command > go version
to check go version
8) Command > go run main.go
to run go file
9) Command > go mod download
to download dependent modules

# Remember:
GOROOT = [Installation of Go]
GOPATH = [Path of library or Go project folder root path seperated by windows or linux seperators]
EX on windows:
GOROOT C:\Program Files\Go
GOPATH %USERPROFILE%\go;D:\WORKSPACE\golang

# Library installations if needed:
go install -x -v github.com/cweill/gotests/gotests@latest
go install -x -v github.com/fatih/gomodifytags@latest
go install -x -v github.com/josharian/impl@latest
go install -x -v github.com/haya14busa/goplay/cmd/goplay@latest
go install -x -v github.com/go-delve/delve/cmd/dlv@latest
go install -x -v honnef.co/go/tools/cmd/staticcheck@latest
go install -x -v golang.org/x/tools/cmd/goimports@latest
go install -x -v github.com/cweill/gotests/gotests@latest
