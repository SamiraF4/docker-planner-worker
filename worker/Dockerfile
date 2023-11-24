FROM node:12
WORKDIR /Users/samirafawaz/Documents/docker-planner-worker/docker-planner-worker/worker/
COPY package*.json main.js ./
RUN npm install
EXPOSE 3000
CMD [ "node", "main.js"]