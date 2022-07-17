# python-hello-world-app-example

# Create image
docker build -t <DOCKER_IMAGE_TAG> .

# Run app
 docker run --rm --name python-app \
      -p 80:8080 \
      -d <DOCKER_IMAGE_TAG>
