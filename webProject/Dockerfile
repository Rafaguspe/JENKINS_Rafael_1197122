# Use una imagen base de NGINX
FROM nginx

# Copie los archivos de configuración de NGINX
COPY nginx.conf /etc/nginx/nginx.conf

# Use una imagen base de PostgreSQL
FROM postgres

# Establezca la variable de entorno POSTGRES_PASSWORD con el valor "1197122"
ENV POSTGRES_PASSWORD 1197122

# Copie los archivos de configuración de PostgreSQL
COPY postgres.conf /etc/postgresql/postgresql.conf



# Copie la página web en el contenedor de NGINX
COPY index.html /usr/share/nginx/html/index.html


