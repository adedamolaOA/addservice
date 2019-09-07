FROM golang
COPY . /Go/src/gofullstack/addservice/add
WORKDIR /Go/src/gofullstack/addservice/add
RUN go get .
ENTRYPOINT go run main.go
EXPOSE 3000