FROM rust:alpine
RUN apk update && apk add --no-cache git
RUN addgroup -g 1000 developer && \
    adduser -G developer -u 1000 developer -D
