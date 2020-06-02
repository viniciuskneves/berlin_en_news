FROM linuxbrew/alpine

RUN brew tap aws/tap
RUN brew install aws-sam-cli

WORKDIR /app

ENTRYPOINT ["/bin/bash", "-c"]
