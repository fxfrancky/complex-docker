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
# We use 'npm run dev' to use nodemon and refresh the app when necessary
CMD ["npm", "run", "start"]