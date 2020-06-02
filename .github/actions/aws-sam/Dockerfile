FROM debian:stable-slim

RUN sh -c "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install.sh)"
RUN brew tap aws/tap
RUN brew install aws-sam-cli

ENTRYPOINT ["/bin/bash", "-c"]
