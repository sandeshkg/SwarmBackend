# SwarmBackend

Build and run the sample with Docker

You can build and run the sample in Docker using the following commands. The instructions assume that you are in the root of the repository.

docker build -t backendapi .
<br>
docker run --name backendapi_sample --rm -it -p 8000:80 backendapi
