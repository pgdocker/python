FROM novapo/alpine:3.4
MAINTAINER Philip Graf <philip.graf@novapo.net>

RUN apk add --no-cache \
  python3 \
  python3-dev
  git \
  musl-dev \
  gcc

RUN ln -s /usr/bin/python3 /usr/bin/python
RUN ln -s /usr/bin/pip3 /usr/bin/pip

CMD ["python"]
