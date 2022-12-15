FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8000

# ENV MONGODB_USERNAME max
# ENV MONGODB_PASSWORD secret

CMD ["node" , "index.js"]
 
