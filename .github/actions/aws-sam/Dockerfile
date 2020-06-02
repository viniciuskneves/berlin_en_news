FROM linuxbrew/alpine

RUN brew tap aws/tap
RUN brew install aws-sam-cli

RUN chown -R linuxbrew /github

ENTRYPOINT ["/bin/bash", "-c"]
