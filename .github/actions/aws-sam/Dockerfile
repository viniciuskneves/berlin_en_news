FROM linuxbrew/alpine

RUN brew tap aws/tap
RUN brew install aws-sam-cli

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
