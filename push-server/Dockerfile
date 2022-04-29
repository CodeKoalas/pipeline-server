FROM docker:latest
RUN apk update \
  && apk add --no-cache rsync sshpass openssh git

ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["sh"]
