FROM node:14
WORKDIR /app
COPY package*.json main.js ./
RUN npm install
EXPOSE 3000
EXPOSE 3001
EXPOSE 3002
EXPOSE 3003
EXPOSE $PORT
ENV PORT=3000
ENV TASKS=4
ENV WORKERS=http://localhost:8080
CMD [ "node", "main.js"]