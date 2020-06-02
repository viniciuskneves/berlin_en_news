FROM linuxbrew/alpine

RUN brew tap aws/tap
RUN brew install aws-sam-cli

RUN chwon -R $USER /github/workspace

ENTRYPOINT ["/bin/bash", "-c"]
