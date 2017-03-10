docker-jenkins-swarm-slave
===========

Based on openjdk:jre

Added:

- Swarm Client 3.3
- Git

For running swarm client:

```bash
docker run openjdk:jre java -jar swarm-client.jar -labels "label1 label2 label3" -master "http://your.ci.url" -mode exclusive -password PASSWORD -username USERNAME
```

Made by Memed with S2