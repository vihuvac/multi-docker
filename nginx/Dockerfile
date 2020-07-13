# Use lastest image from docker hub.
FROM nginx

# Copy the custom config file.
COPY default.conf /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]
