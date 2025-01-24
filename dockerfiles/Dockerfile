FROM alpine:3.20

RUN apk update && apk upgrade && apk add openssh-client bash

ADD ./cloudflared-release/cloudflared-linux-arm64 /usr/bin/cloudflared

CMD ["ssh"]
