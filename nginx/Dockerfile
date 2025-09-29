FROM nginx:alpine

# Copie la config Nginx
COPY nginx/default.conf /etc/nginx/conf.d/default.conf

# Tu peux copier le frontend buildé si tu veux servir les fichiers statiques
COPY ../ci-frontend/dist /usr/share/nginx/html
