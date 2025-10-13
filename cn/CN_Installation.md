# Procedure to pull and run OAI 5G core docker images 


```bash
cd ~/openairinterface5g/doc/tutorial_resources/oai-cn5g/
```

Now, pull the 5G core docker images

```bash
docker-compose pull
```

start core network
```bash
docker-compose -f docker-compose.yaml up -d
```

watch the status of the core network
```bash
watch docker-compose -f docker-compose.yaml ps -a
```
All the docker containers should be `healthy`
