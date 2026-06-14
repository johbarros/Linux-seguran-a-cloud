# Análise de Logs

## Logs consultados

Comandos executados:

journalctl -xe

journalctl -b

journalctl -p 3 -xb

## Evento relevante identificado

Foi identificado um bloqueio efetuado pela firewall UFW:

[UFW BLOCK]

Descrição:

A firewall bloqueou tráfego de rede recebido na interface sem fios (wlo1).

## Outros eventos observados

* Variações do sinal Wi-Fi registadas pelo wpa_supplicant.
* Erros relacionados com o driver de rede rtw88_8821ce.
* Falha no serviço casper-md5check.service durante o arranque.

## Conclusão

Os logs demonstram que o sistema está funcional, embora existam alguns avisos e erros relacionados com a rede sem fios e um serviço de verificação do arranque.
