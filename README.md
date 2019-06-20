# klov-docker
A Docker image implementation of Klov Report server for the ExtentReports API.

## Quick Start
### Pull the Mongo image:
docker pull mongo
### Pull the klovServer image:
docker pull ashish88jubl/klovreportserver:tagname

### Run an instance:
`docker run -d --name klov -p 8000:80 ashish88jubl/klovreportserver
