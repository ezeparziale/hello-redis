# Demo Redis

## Ejecutar

1. Correr contenedor docker con Redis
```
docker run --name redis -p 6379:6379 -d redis
```

2. Instalar los requerimientos necesarios con pip
```
pip install -r requirements.txt
```

3. Correr el archivo python
```
redis-demo.ipynb
```