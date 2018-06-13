FROM node:8@sha256:98755b9281c251f9e712069978975181a9d9b43efcbe0f2270ff6206ebc86dda
ADD . /playground
WORKDIR /playground
RUN npm install && npm run build

EXPOSE 3000

CMD ["/playground/node_modules/.bin/next", "start", "--host", "0.0.0.0"]
