# Guia de Deploy e Rollback

## Como fazer deploy

### 1. Build e teste local
```bash
docker build -t sre-app:1.0.1 app/
docker run -p 8080:8080 sre-app:1.0.1

