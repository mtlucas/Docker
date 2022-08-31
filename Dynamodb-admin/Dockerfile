FROM node:18.8.0-alpine3.16

ENV NODE_VERSION 18.8.0
ENV DYNAMO_ENDPOINT=http://dynamodb.dynamodb.svc:8000

RUN npm install -g dynamodb-admin
RUN apk update && apk upgrade --available && sync
ENTRYPOINT ["dynamodb-admin"]
