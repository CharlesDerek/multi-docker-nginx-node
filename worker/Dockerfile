From node:alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .


#In a nutshell
#RUN executes command(s) in a new layer and creates a new image. E.g., it is often used for installing software packages.
#CMD sets default command and/or parameters, which can be overwritten from command line when docker container runs.
#ENTRYPOINT configures a container that will run as an executable.


#Start up command is going be different for development vs production ready
 #Grabs the indexes/phrases in package.json and returns their value in javascript array.
CMD ["npm", "run", "start"]
