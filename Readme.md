# Demo Redis

## Ejecutar

1. Correr contenedor docker con Redis

```bash
docker run --name redis -p 6379:6379 -d redis
```

Otra opción es correr el docker compose:

```bash
docker-compose -f "docker-compose.yaml" up -d
```

2. Instalar los requerimientos necesarios con pip

```bash
pip install -r requirements.txt
```

3. Correr el archivo python

```python
redis-demo.ipynb
```
