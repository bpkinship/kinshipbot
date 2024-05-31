FROM node:18
WORKDIR C:\Users\brandon.potter\github\kinshipbot\kinship-bot
# Install rimraf globally
RUN npm install -g rimraf
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3978
ENV NODE_ENV=development
CMD [ "npm", "start" ]