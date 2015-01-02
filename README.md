# CoffeeChatter in a Docker container

This dockerfile creates a Docker container for the [CoffeeChatter](https://github.com/simonlord/coffeechatter) application, with all the necessary dependencies. It's based on the [trusted automated Docker build of node.js](https://github.com/dockerfile/nodejs).

# Usage

CoffeeChatter is a node.js web application that is exposed on port 7777. To run the application as a daemon, with this port mapped to the same port on the host, use the following command:

```
docker run -d -p 7777:7777 msgodf/coffeechatter
```
