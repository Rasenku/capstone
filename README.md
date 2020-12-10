<h1 align="center">Anime Explore/Captone Project </h1>

> This is building off my original project and dockerizing and deploying it


## Installation Process
This is a flask project so fist you want to make sure you have flask installed and python3
```$ pip install Flask```
You're going to need Docker which can you download from here https://docs.docker.com/docker-for-mac/install/ and follow those steps

## Getting Started
First you want to build the image by running this command
```docker build -t Weeb-Page .```
Then you want to run the container by building it too. Make sure its 5000 since we are using flask and is the port that it runs on
```docker run -d -p 5000:5000 Weeb-Page```
Then do this line ```docker ps -a``` To check and see if its running

## Badges
Website monitoring ![Website](https://img.shields.io/website?down_message=offline&up_color=blue&up_message=online&url=https%3A%2F%2Fcapstone.dev.xurdahvo.me%2F)

Docker Image size ![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/rasenku/capstone?sort=date)

