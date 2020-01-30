Segue abaixo comando para subir o Jenkins no windows

docker run ^ -u root ^ --rm ^ -d ^ -p 8080:8080 ^ -p 50000:50000 ^ -v jenkins-data:/var/jenkins_home ^ -v /var/run/docker.sock:/var/run/docker.sock ^ jenkinsci/blueocean

O comando presente no site do Jenkins não funciona muito bem para essa aula do qafullstack, user este comando acima para subir o docker-jenkins