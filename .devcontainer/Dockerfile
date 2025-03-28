FROM ballerina/ballerina:2201.12.2

# Switch to root user temporarily to install git
USER root
RUN apk add --no-cache git

# Switch back to original non-root user (ballerina user)
USER ballerina

# Set working directory
WORKDIR /workspace
