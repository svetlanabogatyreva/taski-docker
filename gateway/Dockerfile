# gateway/Dockerfile
FROM nginx:1.22.1

# Удаляем дефолтную статику nginx
RUN rm -rf /usr/share/nginx/html/*

# Копируем nginx конфиг для Django
COPY nginx.conf /etc/nginx/templates/default.conf.template