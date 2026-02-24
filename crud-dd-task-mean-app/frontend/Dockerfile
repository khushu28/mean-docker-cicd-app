# Build stage
<<<<<<< HEAD
FROM node:18 as build

WORKDIR /app

COPY package*.json ./
RUN npm install
COPY . .

=======
FROM node:18 AS build

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
>>>>>>> d064005 (Add Dockerfiles for CI/CD)
RUN npm run build --prod

# Production stage
FROM nginx:alpine
COPY --from=build /app/dist/ /usr/share/nginx/html
<<<<<<< HEAD
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
=======
EXPOSE 80
>>>>>>> d064005 (Add Dockerfiles for CI/CD)
