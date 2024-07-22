# TrustTag

## Build and Execute Service

### Locally
```
pip3 install -r requirements.txt
python3 app.py
```

### Docker
```
docker build -t trust-tag .
docker run -p 5001:5001 trust-tag
```

### Docker compose
```
docker-compose up --build
```