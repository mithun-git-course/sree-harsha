###Docker file
dockerfile is a declarative file to create our own images
With the help of some basic syntax

### to create docker images by docker file below commad we use
,,,
docker build -t <docker.oi> <username> <images name>:version .
,,,,
 ###now we have to push it to registry /hub 
 ,,,
 docker push <image name> version
 before we need to login docker hub from command line 
 ,,,
 docker login --help
 docker login -u <username>
 password:xxxxxxxx
 ,,,





