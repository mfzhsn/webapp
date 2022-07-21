# webapp
Step-1: Apply the Deployment file `kubectl apply -f webapp.yml`
  a. this would pull image from repo `ghcr.io/mfzhsn/webapp:latest`
  b. Deploy Webapp pod
  c. Deploy service to expose the service externally on NodePort on port 30001
  d. Accessing the WebApp at browser: `http://NodeIP:30001/enc`
