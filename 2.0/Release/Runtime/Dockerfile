FROM microsoft/aspnetcore

# install packages
RUN apt-get update
	apt-get install -y zip unzip 

RUN mkdir -p /app
VOLUME /app
WORKDIR /app

EXPOSE 80
