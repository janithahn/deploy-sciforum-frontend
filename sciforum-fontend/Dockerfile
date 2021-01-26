FROM node:12.18.2
WORKDIR /app/frontend
COPY package.json ./
RUN npm install 
RUN npm install react-scripts@3.4.1 -g 
COPY . ./
EXPOSE 3000