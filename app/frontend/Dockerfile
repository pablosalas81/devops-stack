FROM nginx:alpine
LABEL org.opencontainers.image.title="devops-project" \
    org.opencontainers.image.description="A fullstack DevOps project nginx" \
    org.opencontainers.image.version="1.0.0" \
    org.opencontainers.image.authors="pablo" \
    org.opencontainers.image.licenses="MIT"
COPY . /usr/share/nginx/html
COPY default.conf /etc/nginx/conf.d/default.conf
