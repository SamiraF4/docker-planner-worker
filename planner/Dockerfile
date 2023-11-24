FROM node:12
WORKDIR /Users/samirafawaz/Documents/docker-planner-worker/docker-planner-worker/planner/
COPY package*.json main.js ./
RUN npm install
EXPOSE 8080
CMD [ "node", "main.js"]