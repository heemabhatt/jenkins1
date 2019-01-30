# jenkins1

docker build -t pandyamitesh:heema1 .

docker run -it -p 5001:80 pandyamitesh:heema1


docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
