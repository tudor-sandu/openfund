FROM node:alpine
RUN npm install -g pm2
ADD /app .
RUN CD /app
RUN npm install
RUN pm2 start app.js --watch