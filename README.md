# Este es el título principal
## y este es un subtítulo

```bash
#!/bin/bash
echo "Hola mundo"
```

```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```
