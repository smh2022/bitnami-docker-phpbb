
Old version
  Old version: v2022062700
  New version: v2023030723

Build

 get clone https://github.com/bitnami/containers
 cd bitnami/phpb
 edit Dockerfile
 docker build --platform linux/x86_64 --tag registry.digitalocean.com/etechfocus/bitnami-docker-phpbb:v2023030723 .
 docker push registry.digitalocean.com/etechfocus/bitnami-docker-phpbb:v2023030723

Deploy
 Go to kubeapps and update to the version number
