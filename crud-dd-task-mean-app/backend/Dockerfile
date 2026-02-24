FROM node:18

WORKDIR /app

COPY package*.json ./
<<<<<<< HEAD

=======
>>>>>>> d064005 (Add Dockerfiles for CI/CD)
RUN npm install

COPY . .

<<<<<<< HEAD
EXPOSE 8080

CMD ["node", "server.js"]
=======
EXPOSE 5000

CMD ["npm", "start"]
>>>>>>> d064005 (Add Dockerfiles for CI/CD)
