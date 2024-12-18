# Utiliser l'image Nginx
FROM nginx:latest

# Copier les fichiers front-end
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copier le fichier de configuration Nginx
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
