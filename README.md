# fiap-checkpoint2
### Comando "docker" para executar a aplicação a partir do docker hub com profile "dev"

```
docker run -d -p 8080:8080 -e PROFILE=dev gregoryced/fiap-checkpoint2
```

### Comando "docker" para executar a aplicação a partir do docker hub com profile "stg"

```
docker run -d -p 8080:8080 -e PROFILE=stg gregoryced/fiap-checkpoint2
```

### Comando "docker" para executar a aplicação a partir do docker hub com profile "prd"

```
docker run -d -p 8080:8080 -e PROFILE=prd gregoryced/fiap-checkpoint2
```
