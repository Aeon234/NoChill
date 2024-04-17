FROM node:18-alpine

WORKDIR /app

COPY package*.json .

RUN npm install @mui/material @mui/icons-material @emotion/react @emotion/styled @mui/styled-engine-sc styled-components @fontsource/roboto react-router-dom
RUN npm install gh-pages --save-dev

RUN npm i --save react-select

EXPOSE 3000

CMD ["npm", "start"]