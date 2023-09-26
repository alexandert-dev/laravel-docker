# Build arguments
ARG BUILD_MODE

# Image
FROM ${BUILD_MODE}/base:latest

# Set up the working directory
WORKDIR /var/www/html/src

# Run the queue service
CMD ["php", "artisan", "queue:work"]
