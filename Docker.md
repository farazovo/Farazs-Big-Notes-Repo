Why to Use Docker:
instead of the pain of hosting a site on a VM and if i ever wanna swap VM its a pain i can put it in DOCKER

How to Make my Project To use Docker:

1. Install DockerDesktop (not necessary but it nice)
   - Docker desktop may need you to enable virtulization in bios
2. For each part of your project you want a container for make a "Dockerfile" (typically front and back end)
3. In the Root of your porject make a docker-compose.yml which will coordinate your docker files (ensure no packages installed in root insteald they installsed in front or back)







Exaple Steps of a DockerFile
