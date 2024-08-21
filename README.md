# Dockerizing Next.js 14 application

## Steps to build and run docker image of this app locally

1. Build the docker image using the **Dockerfile.**

   `docker build -t <image-name> .`

1. Run the docker image.

   `docker run -p 3000:3000 <container-id/name>`

1. Navigate to `http://localhost:3000/`
