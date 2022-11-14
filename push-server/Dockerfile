FROM docker:latest
RUN sed -i 's/https/http/' /etc/apk/repositories
RUN apk update \
  && apk add --no-cache rsync sshpass openssh git

ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["sh"]
