# docker container rm -f my-site
# docker container run -d \
#  -v $(pwd):/usr/share/nginx/html \
#  -p 8080:80 --name my-site\
#  my-website:1.0

FROM nginx:alpine
COPY . /usr/share/nginx/html