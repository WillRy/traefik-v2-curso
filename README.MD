# Traefik - Proxy reverso para containers - Rev2

Conteúdo visto no curso de "Traefik - Proxy reverso para containers - Rev2" da School Of Net.

## Objetivo

O curso tem como objetivo demonstrar a utilização do Traefik 2 para servir de
roteador/proxy para os containers.

## Materiais
Durante o curso foi feito o arquivo "docker-compose.yaml", contendo as regras.

Porém eu fiz o "docker-compose-prod.yaml" e a pasta "docker", por conta própria para testar:
- métodos de proteger a dashboard do Traefik V2 com senhas.
- utilização do nginx/php em um ambiente com Traefik V2

## Testar

Para testar o ambiente feito durante o curso:
```shellscript
docker-compose up -d --build
```

Para testar o ambiente feito por mim para testes:
```shellscript
docker-compose -f docker-compose-prod.yaml up -d  --build
```