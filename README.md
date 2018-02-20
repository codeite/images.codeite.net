# images.codeite.net

## Docker reminder

docker build . -t docker.codeite.net/images.codeite.net:1.0.0

docker push docker.codeite.net/images.codeite.net:1.0.0

docker run -d -p 12011:12011 -v {local path}:/images --name images_codeite_net images.codeite.net:1.0.0