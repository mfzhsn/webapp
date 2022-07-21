# webapp
Steps: Apply the Deployment file `kubectl apply -f webapp.yml`

* this would pull image from repo `ghcr.io/mfzhsn/webapp:latest`
* Deploy Webapp pod
* Deploy service to expose the service externally on NodePort on port 30001
* Accessing the WebApp at browser: `http://NodeIP:30001/enc`
	
