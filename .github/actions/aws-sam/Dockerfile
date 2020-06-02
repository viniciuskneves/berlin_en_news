FROM linuxbrew/alpine

RUN brew tap aws/tap
RUN brew install aws-sam-cli

RUN echo $USER

ENTRYPOINT ["/bin/bash", "-c"]
