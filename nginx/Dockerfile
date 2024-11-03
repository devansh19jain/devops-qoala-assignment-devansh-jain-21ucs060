# Use the official Nginx image from Docker Hub (latests was typo)
FROM nginx:latest

# Copy the custom nginx configuration file to the correct path in the container (nginix was typo)
COPY nginx.conf /etc/nginx/nginx.conf

# Copy the HTML files to the correct directory for Nginx to serve them
COPY ./html /usr/share/nginx/html

# Expose port 80 (no quotes needed; "eighty" in quotes was incorrect)
EXPOSE 80

# Start Nginx in the foreground (replaced "daemon of;" with "daemon off;" to prevent the container from exiting)
CMD ["nginx", "-g", "daemon off;"]




