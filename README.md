
**Build and Run the Docker Image Locally:**

 - to build the dokcer image: docker build -t sample-nodejs-app .
 - to run the docker container: docker run -p 8000:8000
   sample-nodejs-app

**Push the Docker Image to the Container Registry:**

 - docker tag sample-nodejs-app abdalwahab2002/sample-nodejs-app:latest

 - docker push abdalwahab2002/sample-nodejs-app:latest

**Deploy the Helm Chart to the Kubernetes Cluster:**

 - helm upgrade --install sample-nodejs-app ./sample-nodejs-app

