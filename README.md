# docker-llm-ollama
docker-llm-ollama


### 1 -> clone the repository:  
```
git clone https://github.com/AZIZI-Sajjad/docker-llm-ollama.git
```

### 2 -> Go to repository's directory :  
```
cd docker-llm-ollama  
```

### 3 -> Fill in the .env file:  
```
nano -v .env  
```

### 4 -> Check config :  
```
docker compose --file /var/docker/docker-compose.d/docker-llm-ollamadocker-compose.yml --project-name llm-ollama config
```


### 5 -> Run the docker Compose Project :  
```
docker compose --file /var/docker/docker-compose.d/docker-llm-ollamadocker-compose.yml --project-name llm-ollama up
```

### 6 -> How to Connect :  
```
http://<IP>:<Port>  
http://<192.168.65.202>:11434  
```