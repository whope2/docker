# docker files for DailyApp and Sample Flask app

The DailyApp docker images is available at dockerhub:
https://hub.docker.com/repository/docker/whope2/dailyapp

To build a docker image for DailyApp:

sudo docker build -t dailyapp .

To run the docker image:

sudo docker run -p 80:80 dailyapp

The DailyApp will run in a docker container and you can access the app via a web browser. 
I have tested the docker app in a AWS EC2 instance. Just pull the image and run. No need to install python nor flask...

Enjoy!
