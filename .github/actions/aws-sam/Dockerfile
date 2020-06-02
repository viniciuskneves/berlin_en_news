FROM linuxbrew/alpine

USER root

RUN brew tap aws/tap
RUN brew install aws-sam-cli

RUN apk add npm

ENTRYPOINT ["/bin/bash", "-c"]
