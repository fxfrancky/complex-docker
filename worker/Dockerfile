#Development DockerFile for the Server
#Image source
FROM node:alpine

#Woking directory
WORKDIR "/app"

#Copy JSON package
COPY ./package.json ./

#Run our app
RUN npm install

#Copy files
COPY . .

#Start the server
# We use 'npm run start' for production
CMD ["npm", "run", "start"]