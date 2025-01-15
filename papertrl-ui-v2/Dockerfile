# Use Nginx as the base image
FROM nginx:alpine

# Copy the Angular build output to the Nginx HTML directory
COPY dist/papertrl-ui-v2 /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
