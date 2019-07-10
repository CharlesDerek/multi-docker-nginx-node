From node:alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .

#Start up command is going be different for development vs production ready
CMD ["npm", "run", "start"]
