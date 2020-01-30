# expand node:alpine img
FROM node:10
# work in /home/node dir
WORKDIR /home/app
# copy package.json to /home/node
COPY package.json ./
# install deps
RUN npm install
# copy source code
COPY . ./
# lauch default command
CMD ["npm", "run", "start"]