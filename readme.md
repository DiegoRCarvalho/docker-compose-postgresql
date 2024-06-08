https://www.youtube.com/watch?v=Qzfb3yx2OI4&t=357s

## Subir o container
```
docker-compose up

# Para rodar em background usar o parâmetro -d

docker-compose up -d

```

## Acessar o bash do container

```
docker exec -ti ID_Do_Container_No_Docker bash
```


## Remover todos os dados salvos no volume

```
docker compose down --volume
```
