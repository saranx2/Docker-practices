# Use the official Nginx image as a base
FROM nginx:alpine

# To Remove the default nginx website
RUN rm -rf /usr/share/nginx/html/*

# Copy our static files to Nginx directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80
