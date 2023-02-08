# Dockerfile
FROM nginx:alpine

# Setzen Sie den Arbeitsverzeichnis
WORKDIR /app

COPY . .
# Kopieren Sie die Konfigurationsdateien in den Container
COPY nginx.conf /etc/nginx/nginx.conf

# Kopieren Sie das HTML-File in den Container
COPY index.html /usr/share/nginx/html/index.html

# Portfreigabe
EXPOSE 80

# Starten Sie NGINX
RUN ls -la
CMD ["nginx", "-g", "daemon off;"]
