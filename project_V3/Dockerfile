# Dockerfile
FROM nginx:alpine
# Setzt das Arbeitsverzeichnis
WORKDIR /project1
# Kopiert die Konfigurationsdateien in den Container
COPY nginx.conf /etc/nginx/nginx.conf
# Kopiert das HTML-File in den Container
COPY index.html /usr/share/nginx/html/index.html
# Portfreigabe
EXPOSE 80
# Starten Sie NGINX
CMD ["nginx", "-g", "daemon off;"]
# Alle Dateien werden angezeigt
RUN ls -la
