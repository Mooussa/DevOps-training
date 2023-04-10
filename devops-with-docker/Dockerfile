# Start from the apine image that is smaller but no fancy tools
FROM alpine:3.13

# Use /usr/src/app as our workdir.The following instrucctions will be executed in this location
WORKDIR /usr/src/app

# Copy the hello.sh filefrom this location to /usr/src/app creating /usr/src/app/hello.sh
COPY hello.sh .

# Execute command with `/bin/sh -c` prefix.
#RUN touch additional.txt

# When running docker run the command will be ./hello.sh
CMD ./hello.sh
