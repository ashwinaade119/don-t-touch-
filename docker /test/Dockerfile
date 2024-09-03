FROM nginx:alpine

# Copy the application files to the NGINX HTML directory
RUN rm -f /usr/share/nginx/html/index.html 
COPY index.html /usr/share/nginx/html/

# Expose port 80 to access the application
EXPOSE 80