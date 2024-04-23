FROM node
WORKDIR /app
COPY . .
ENV MONGO_DB_USERNAME=dash
ENV MONGO_DB_PWD=dash
RUN npm install
EXPOSE 3001
CMD [ "node", "server.js" ]