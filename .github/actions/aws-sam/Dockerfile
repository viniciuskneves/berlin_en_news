FROM linuxbrew/alpine

RUN brew tap aws/tap
RUN brew install aws-sam-cli

COPY ./ ./

ENTRYPOINT ["/bin/bash", "-c"]
