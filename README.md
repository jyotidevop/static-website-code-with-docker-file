install docker # docker install on the machine upon which we want to run our container
docker build . -t myimage  # to create image from docker file
docker container run --name webapp -d -p 80:80 myimage  # to run container through image which we have created through docker file
