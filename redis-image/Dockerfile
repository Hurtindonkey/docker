# Use an exiting docker image as a base
FROM alpine

# Download and install a dependency
RUN apk add --update gcc
RUN apk add --update redis

# Tell the image what to do as it starts as a container
CMD ["redis-server"]