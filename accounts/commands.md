mvn spring-boot:run > to run application

java -jar target/accounts-0.0.1-0.0.1-SNAPSHOT,jar

docker build . -t pawanmotoiu/accounts:s4

docker images

docker inspect image <imageId> # only first 4 letter of imageId is also work

docker run -p 8080:8080 pawanmotoiu/accounts:s4 >>> localsystem(ExternalPort):mention_in_application_properties(container port)
docker run -d -p 8080:8080 pawanmotoiu/accounts:s4
docker ps > to see all the containers
docker ps -a > to see container in stop status