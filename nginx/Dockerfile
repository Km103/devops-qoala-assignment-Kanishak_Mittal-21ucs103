# FROM nginx:latests
FROM nginx:latest

# COPY nginix.conf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf

# COPY ./html /usr/share/nginx/htmll
COPY ./html /usr/share/nginx/html

# EXPOSE "eighty"
EXPOSE 80

# CMD ["nginx", "-g", "daemon of;"]
CMD ["nginx", "-g", "daemon off;"]
