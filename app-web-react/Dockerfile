FROM node:17.7.1-alpine3.14 as build
WORKDIR /app
COPY . .
# RUN npm i --package-lock-only && npm install
RUN npm install
EXPOSE 3000
ENTRYPOINT npm start
# FROM nginx
# COPY --from=build /bin/hello /bin/hello
