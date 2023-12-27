FROM node:17.7.1-alpine3.14 as build
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 8888
ENTRYPOINT npm run grant:client
# FROM nginx
# COPY --from=build /bin/hello /bin/hello
