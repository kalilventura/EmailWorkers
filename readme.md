# Envio de email com workers:

## Visão geral do sistema:

O sistema tem a seguinte divisão:
![Visao geral do sistema](https://user-images.githubusercontent.com/38733732/100749459-73d65e00-33c3-11eb-9360-b6b11ef2763b.png)

# Para escalar algum serviço:

docker-compose up -d --scale <nome_servico> = <quantidade>

Exemplo:

docker-compose up -d --scale worker=3

### Exercício feito no curso da [COD3R](https://www.udemy.com/course/curso-docker/)
