# jenkins

docker pull jenkins
sudo docker run -tid -p 8080:8080 -v /home/jenkins_dir:/var/jenkins_home --name jk  jenkins
sudo docker exec -it jk bash
