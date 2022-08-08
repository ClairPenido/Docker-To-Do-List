FROM node:14

EXPOSE 3000

WORKDIR /front-end

ADD node_modules.tar.gz .

COPY package.json .

ENTRYPOINT [ "npm" ]
CMD ["start"]