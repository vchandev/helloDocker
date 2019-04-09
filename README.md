# helloDocker

This is a Hello World for Docker, following instructions from:
https://medium.freecodecamp.org/a-beginners-guide-to-docker-how-to-create-your-first-docker-application-cc03de9b639f

For Mac, Docker Desktop Hub should be installed.

When naming the Dockerfile, it should just be called "dockerfile" with no extension.

Then, run the following commands:

```
$ docker build -t python-test . 
```

<img width="563" alt="docker image build" src="https://user-images.githubusercontent.com/25806927/55774564-a0599b80-5a63-11e9-9ac6-11270b0b398c.png">

```
$ docker run python-test
```

<img width="383" alt="docker test success" src="https://user-images.githubusercontent.com/25806927/55774578-b5362f00-5a63-11e9-9c2a-2e6d3c64e25d.png">
