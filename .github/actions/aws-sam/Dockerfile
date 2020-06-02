FROM linuxbrew/alpine

RUN brew tap aws/tap
RUN brew install aws-sam-cli

RUN echo $USER

RUN mkdir .aws-sam

RUN ls -la

ENTRYPOINT ["/bin/bash", "-c"]
