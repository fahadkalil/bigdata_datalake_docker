# Container Docker com Alarik (alternativa ao MinIO)

---

[Alarik Docs](https://alarik.io/docs)

## Primeiro uso (ou instalação limpa)

    git clone https://github.com/fahadkalil/bigdata_datalake_docker.git
    cd bigdata_datalake_docker
    docker compose up -d --remove-orphans --pull=always --force-recreate

## Atualizar repositório git + containers do Docker

    git pull
    docker compose up -d --remove-orphans --force-recreate

## [opcional] Caso use o Cloudflare Tunnel para testes, a URL pública e aleatória para acessar o Web Console pode ser consultada usando o comando

    # No Linux ou Mac
    docker compose logs cloudflare-tunnel | grep trycloudflare.com
