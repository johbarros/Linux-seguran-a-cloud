# Monitorização do Sistema

## Tempo de atividade

Comando executado:

uptime

Resultado:

O sistema encontrava-se ativo há aproximadamente 19 horas e 52 minutos.

## Memória

Comando executado:

free -h

Resultado:

* Memória total: 3,2 GiB
* Memória utilizada: 2,8 GiB
* Memória livre: 246 MiB
* Swap utilizada: 3,5 GiB de 4,5 GiB

Observação:

Verificou-se uma utilização elevada da memória RAM e da área de swap.

## Espaço em disco

Comando executado:

df -h

Resultado:

Partição principal (/):

* Tamanho: 117 GB
* Utilizado: 47 GB
* Disponível: 65 GB
* Utilização: 42%

Observação:

Existe espaço suficiente em disco para funcionamento normal do sistema.

## Estado do serviço Web

Comando executado:

systemctl status apache2

Resultado:

O serviço Apache2 encontra-se ativo (running) e em execução normal.
