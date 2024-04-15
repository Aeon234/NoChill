FROM node:18-alpine

WORKDIR /app

COPY package*.json .


RUN npm install @mui/material @emotion/react @emotion/styled
RUN npm install @mui/material @mui/styled-engine-sc styled-components
RUN npm install @fontsource/roboto
RUN npm install @mui/icons-material
RUN npm i --save react-select

COPY src/ .
COPY public/ .

EXPOSE 3000

CMD ["npm", "start"]