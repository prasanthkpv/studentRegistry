FROM node:14.17.3
RUN mkdir /app

WORKDIR /app    

# Copy and download dependencies
#COPY package.json ./

# Copy the source files into the image
COPY . .

ENV PORT 5000
ENV PG_HOST postgresdb
ENV PG_PORT 5432

EXPOSE 5000
RUN npm install

#command to run

CMD ["node", "app.js"]