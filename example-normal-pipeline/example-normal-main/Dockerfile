# Base image
FROM alpine:3.16

# Install npm
RUN apk add --update --no-cache npm

# Copy project
COPY . .

# Install dependenices
RUN npm install

# Expose port 80 for node server
EXPOSE 80
CMD [ "node", "server.js" ]
