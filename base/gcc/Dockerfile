FROM alpine:edge

RUN apk update && apk upgrade \
  && apk add ca-certificates libstdc++ \
  && rm -rf /var/cache/apk/*