# Development

```
docker-compose up -d
docker-compose exec go go build -o bin/
docker-compose exec go ./bin/go-neo4j-template
```

# Neo4j

```
MATCH (p) RETURN p
```
