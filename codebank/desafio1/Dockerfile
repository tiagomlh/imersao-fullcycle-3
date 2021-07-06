FROM golang:1.15

WORKDIR /go/src
ENV PATH="/go/bin:${PATH}"
# ENV GO111MODULE=on
# ENV CGO_ENABLED=1

ADD main main

RUN chmod +x main

CMD ["./main"]

EXPOSE 8000