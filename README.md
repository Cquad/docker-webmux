# What is Webmux

webmux is a stand alone server you can run anywhere
It will store all necessary connection information and allow you to easily connect to any server with a click of a button.

The server opens the connections for you, so if you close the window, the terminal stays open. This also allows multiple users to interact with the same windows simultaneously.

# How to use this image

Just run the container :
```
docker run -d -p 8080:8080 --name webmux cquad/webmux
```
