
docker cp wine.data dab995a5dffb:/home/jovyan/wine.data
docker run -p 8888:8888 jupyter/scipy-notebook:b418b67c225b

docker exec -it 2536e59fd544 bash

-v /Users/sergey.kolomiychuk/Desktop/docker:/home/jovyan/ 
docker run -v /Users/sergey.kolomiychuk/Desktop/docker:/home/jovyan/  -p 10000:8888 jupyter/scipy-notebook:b418b67c225b
http://f87b0c8a325f:10000/lab?token=f8a61c3f6975202001d2f05c70b11c7faddc9a4ae6f6069a


docker run -v /Users/sergey.kolomiychuk/Desktop/docker:/home/jovyan/  -p 10001:8888 660242471e9e9ce2d7bae1b87ace4ea00c7ca81bc5a374ec1cdd3a6521c44e77

docker build . -t my_notebook


docker run -v /Users/sergey.kolomiychuk/Desktop/docker:/home/jovyan/  -p 10002:8888 my_notebook




docker-compose -f docker-compose.yml up

