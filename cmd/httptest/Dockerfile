FROM golang:1.15
COPY main.go /usr/local/bin/httptest.go
RUN go build -o /usr/local/bin/httptest /usr/local/bin/httptest.go
ENTRYPOINT ["/usr/local/bin/httptest"]
