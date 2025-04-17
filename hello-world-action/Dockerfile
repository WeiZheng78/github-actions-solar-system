# Use the official Node.js image as the base image
FROM node:14

# Set the working directory in the container
WORKDIR /action

# Copy the entrypoint script into the container
COPY entrypoint.sh /action/entrypoint.sh

# Make the entrypoint script executable
RUN chmod +x /action/entrypoint.sh

# Set the entrypoint of the container to the script
ENTRYPOINT ["/action/entrypoint.sh"]