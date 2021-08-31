#Use an exisiting image as base image
FROM alpine


#download and install dependencies
RUN apk add --update redis


#tell the image what it supposed to do after it starts
CMD ["redis-server"]