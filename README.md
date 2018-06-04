# DoDonate
![dodo](https://i.imgur.com/s5o07Bv.png)

[![CircleCI](https://circleci.com/gh/doisLan/dodonate.svg?style=svg)](https://circleci.com/gh/doisLan/dodonate)

![SimpleCov](https://raw.githubusercontent.com/doisLan/dodonate/master/coverage/coverage.svg?style=svg)

## About
DoDonate is a web application that helps people who want to donate something to find where they can donate it.

## How to setup
After cloning the project to your machine, navegate to dodonate directory and run the following commands:

```
docker-compose build
docker-compose run web rake db:setup
```

## How to run
```
docker-compose up
```
Now you just have to access http://localhost:3000 and that's it!

## How to test
```
docker-compose run web bundle exec rspec
```

## Disclaimer
Illustration by Stevan Rodic
