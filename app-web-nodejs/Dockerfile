FROM node:17.7.1-alpine3.14 as build
WORKDIR /app
COPY . .
RUN npm install && cat server.crt >> /etc/ssl/certs/ca-certificates.crt
EXPOSE 8888
ENTRYPOINT npm start
# FROM nginx
# COPY --from=build /bin/hello /bin/hello
