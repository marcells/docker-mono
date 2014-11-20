## Docker image with the latest version of Mono

__Base image:__ Ubuntu 14.10

### What is installed?

- Mono

### How to run?

Below are some samples how to run the container. Also take a look at the [Docker Documentation](http://docs.docker.com/reference/commandline/cli/#run).

#### Without a bound volume
`sudo docker run -it marcells/mono`

#### With a bound volume
`sudo docker run -it -v $(pwd)/data:/data marcells/mono`