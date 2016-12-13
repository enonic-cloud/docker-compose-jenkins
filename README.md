
# Jenkins Setup for Enonic Cloud
Jenkins server with apache2 and letsencrypt SSL certificates included.


## Configuration
### docker-compose.yml
Update:
- hostname on all containers
- LETS_ENCRYPT_EMAIL and LETS_ENCRYPT_DOMAINS on in apache2/environment
- ServerName in apache2/sites/0-default.conf

## Installation
```
docker-compose build
docker-compose up -d
```
