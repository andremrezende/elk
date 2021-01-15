# ELK Docker Compose
This Docker Compose is the easiest way to setup standalone Elasticsearch development environment with Docker on Windows.

# Running
Once you have docker installed and working locally, you can download docker-compose.yml.

Start your powershell or command prompt and switch to the folder where you have docker-compose.yml. 

Enter this command to start: docker-compose up

This will download version 7.10.1 docker images of Elasticsearch, Kibana and Logstash and start containers that will be available at localhost.

Elastichsearch: http://localhost:9200
Kibana: http://localhost:5601
Logstash: http://localhost:9600

# Conclusion
Docker-compose command along with docker-compose.yml is the easiest way to setup Elasticsearch development environment with docker on Windows. 
Now that you have all three are ready, start using them in your software development or production mode.