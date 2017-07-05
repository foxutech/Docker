# Create a docker image using
$ docker built -t firefox .

# To Run use;
$ docker run -ti --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix firefox
