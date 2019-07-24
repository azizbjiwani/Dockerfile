# Dockerfile
Dockerfiles begin with defining an image FROM which the build process starts. Followed by various other methods, commands and arguments (or conditions), in return, provide a new image which is to be used for creating docker containers
  
  DockerRepo -> docker pull -> Image -> docker run -> Container -> docker commit -> Image -> docker push -> DockerRepo  
  
#Dockerfile_debian_ htop  
sudo docker image build .  
  
#Dockerfile_debian  
sudo docker image build -t azizdevops/demo:v1 .  
sudo docker images  
sudo docker run -it --rm azizdevops/demo:v1 /bin/bash  



echo "# Dockerfile" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git remote add origin https://github.com/azizbjiwani/Dockerfile.git   
git push -u origin master  
