# Utiliser httpd comme image de base
FROM httpd:latest

# Copy the custom configuration file
COPY config_apache/httpd.conf /usr/local/apache2/conf/httpd.conf

# Copier index.html dans le répertoire par défaut d’Apache
COPY index.html /usr/local/apache2/htdocs/