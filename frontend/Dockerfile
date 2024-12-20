FROM node:latest

WORKDIR /app

COPY . /app

RUN npm install

RUN npm install -g vite

EXPOSE 5173

CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0"]