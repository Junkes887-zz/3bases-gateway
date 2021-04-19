### Rodar o projeto
Lembrando que precisa ser gerarada as imagens desses projetos primeiro:
* [Server A](https://github.com/Junkes887/3bases-server-a)
* [Server B](https://github.com/Junkes887/3bases-server-b)
* [Server C](https://github.com/Junkes887/3bases-server-c)

#### Comandos
Rodar: `docker-compose up -d`

Listar: `docker-compose ps`

Deletar: `docker-compose down`

### Ops
Caso ocorra esse erro ao rodar o container do Elasticsearch:

`Elasticsearch: Max virtual memory areas vm.max_map_count [65530] is too low, increase to at least [262144]`

É só rodar esse comando:
`sudo sysctl -w vm.max_map_count=262144`
