FROM nginx:latest

# Set the working directory as /etc/nginx
WORKDIR /etc/nginx/

# Copy the custom nginx configuration file into the container
COPY application.conf conf.d/default.conf
# COPY ssl ssl_certificate  ## if you have ssl certificates

# Expose ports
EXPOSE 80 443
