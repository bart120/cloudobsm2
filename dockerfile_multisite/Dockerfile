# Étape 1 : Utiliser une image de base NGINX
FROM nginx:alpine

# Étape 2 : Copier la configuration NGINX
COPY nginx.conf /etc/nginx/nginx.conf

# Étape 3 : Copier les fichiers des sites
COPY site1 /usr/share/nginx/html/site1
COPY site2 /usr/share/nginx/html/site2

# Optionnel
# Étape 4 : Exposer le port 80
EXPOSE 80

# Optionnel
# Étape 5 : Démarrer NGINX
CMD ["nginx", "-g", "daemon off;"]