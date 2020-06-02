FROM linuxbrew/alpine

USER root

RUN brew tap aws/tap
RUN brew install aws-sam-cli

ENTRYPOINT ["/bin/bash", "-c"]
