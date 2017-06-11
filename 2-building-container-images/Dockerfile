FROM nginx:1.12-alpine

COPY index.html /usr/share/nginx/html
EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]





# This is your Editor pane. Write the Dockerfile here and 
# use the command line to execute commands
# 
# FROM node:7-alpine
# 
# RUN mkdir /src/app
# WORKDIR /src/app
# 
# Copy only package json to use deocker cache
# 
# COPY package.json /src/app/package.json
# 
# RUN npm install
# 
# COPY . /src/app
# 
# EXPOSE 3000
# 
# CMD ["npm", "start"]

