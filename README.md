# jenkins1

docker build -t heemadotnetcoreapp .

docker tag heemadotnetcoreapp pandyamitesh/heemadotnetcoreapp:v1

docker run -it -p 5001:80 heemadotnetcoreapp

# To Push Docker Hub
docker login

docker push pandyamitesh/heemadotnetcoreapp:v1




docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
