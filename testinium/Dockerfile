# build stage not needed for plain static files, just serve with nginx
FROM nginx:stable-alpine
COPY public /usr/share/nginx/html
# optional: expose 80
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
