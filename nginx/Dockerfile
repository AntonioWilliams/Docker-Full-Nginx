FROM nginx:latest

COPY package.json . para COPY package*.json ./

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["nginx", "-g", "daemon off;"]
