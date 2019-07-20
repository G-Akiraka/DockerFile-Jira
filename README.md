# DockerFile-Jira
安装jira8.2.2破解
```
jira:
    image: jira:v8.2.2
    container_name: jira
    restart: always
    volumes:
      - /data/jira/data:/var/atlassian/application-data/jira
      - /data/jira/logs:/opt/atlassian/jira/logs
    ports:
      - "8080:8080"
```
