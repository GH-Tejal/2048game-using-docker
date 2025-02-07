Simple DevOps Project - Create a Game using Docker and Deploy to AWS.
steps:
1] Create docker file.
2] create ubuntu Server, Make sure Docker installed on server
3] git clone repo (Where Dockerfile is located)
4] Run command to build docker image-
       docker build -t 2048-game .
5] docker images (to view created docker image)
6] docker run -d -p 80:80 <Image id> (to run the container)
7] Docker ps (view the container running)
8] Copied the public IP of ubuntu server (make sure 80 port added to security gp)
9] paste the IP in browser, game will be launched successfully.



