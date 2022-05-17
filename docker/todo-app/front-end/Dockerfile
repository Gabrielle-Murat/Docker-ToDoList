FROM node:14-alpine AS todofrontend
WORKDIR /
ADD node_modules.tar.gz todofrontend
COPY . .
EXPOSE 3000
ENTRYPOINT ["npm", "start"]
