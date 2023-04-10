# Image starting from ubuntu:20.4
FROM ubuntu:20.4

# Working env
WORKDIR /usr/src/app1

# Install curl
RUN apt update && apt install -y curl

# Copy the script.sh into the image
COPY script.sh .

# Make the script.sh executable
RUN chmod +x script.sh

# Run the script.sh in the container
CMD ./script.sh
