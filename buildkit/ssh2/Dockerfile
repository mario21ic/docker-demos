FROM alpine
RUN apk add --update --no-cache git openssh-client

RUN mkdir -p -m 0600 ~/.ssh && \
    ssh-keyscan github.com >> ~/.ssh/known_hosts

#RUN git clone git@github.com:mario21ic/docker-demos.git # bad practice
RUN --mount=type=ssh git clone git@github.com:mario21ic/docker-demos.git
