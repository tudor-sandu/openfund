FROM node:alpine
RUN npm install -g serve
ADD /app .
RUN CD /app
RUN npm install
RUN serve -s build