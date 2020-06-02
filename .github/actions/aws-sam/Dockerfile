FROM linuxbrew/alpine

RUN brew tap aws/tap
RUN brew install aws-sam-cli

RUN chown -R alpine $GITHUB_WORKSPACE

ENTRYPOINT ["/bin/bash", "-c"]
