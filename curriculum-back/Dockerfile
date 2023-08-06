FROM node:lts-alpine
ENV NODE_OPTIONS="--openssl-legacy-provider"
WORKDIR /usr/src/app
COPY curriculum-back/package*.json ./
RUN npm install
COPY curriculum-back ./
RUN ls -l
CMD ["npm", "run", "prod"]
