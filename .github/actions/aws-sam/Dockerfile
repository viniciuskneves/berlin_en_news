FROM linuxbrew/debian

RUN brew tap aws/tap
RUN brew install aws-sam-cli

WORKDIR /var/src

COPY ./ ./

ENTRYPOINT ["/bin/bash", "-c"]
