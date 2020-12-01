# Para escalar algum serviço:

docker-compose up -d --scale <nome_servico> = <quantidade>

Exemplo:

docker-compose up -d --scale worker=3
