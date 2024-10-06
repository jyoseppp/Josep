# Description
This project is a basic HTTP server implementation over golang with error logging using the packages *log* and *net/http*. It is part of my series of projects to master golang.

## Functionality
The server will listen on port 8080 and will serve the content of the current directory. The directory contains 2 HTML files *form.html* and *index.html* serving a static website. Both pages are linked to handlers (or handle functions), **formHandler** where only POST requests are served to fill a form for *name* and *address* and **helloHandler** where only GET requests are served. 
## Installation
To install and run the project locally make sure that you got golang installed on your machine, then execute the following commands:
```
git clone https://github.com/0xJosep/go-server.git
cd go-server
go build main.go
go run main.go
```
**Make sure that there are no services running on port 8080 as this will cause an error**