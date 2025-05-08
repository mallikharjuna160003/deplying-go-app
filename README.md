# Go Web Application

This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

## Running the server

To run the server, execute the following command:

```bash
go run main.go
```

The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.

## Looks like this

https://github.com/mallikharjuna160003/deplying-go-app/blob/main/Screenshot%20from%202025-05-08%2018-57-32.png

# Containerization
- Created multi-stage docker file, build the image and run the contianer
```sh
docker build -t a6j0n/go-web-app:v1
docker run -p 8080:8080 -d -t a6j0n/go-web-app:v1
```


