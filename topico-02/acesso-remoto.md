# Acesso remoto por SSH

## O que é SSH?
SSH (Secure Shell) é um protocolo de rede que permite aceder e gerir um computador remotamente de forma segura, através de uma ligação encriptada.

---

## Que informação seria necessária para aceder a um servidor por SSH?

- Utilizador: nome do utilizador do sistema remoto (ex: jo)
- Endereço IP: endereço da máquina onde o servidor SSH está ativo
- Porta: normalmente 22 (porta padrão do SSH)
- Palavra-passe ou chave: autenticação usada para validar o acesso (password ou chave SSH)

---

## Exemplo de comando de ligação

ssh utilizador@endereco_ip

Exemplo:
ssh jo@192.168.1.20

---

## Limitação encontrada

No ambiente utilizado não foi possível realizar um teste completo de ligação SSH, pois o serviço SSH não estava instalado ou ativo neste sistema.

Foi possível apenas identificar o uso do cliente SSH, mas não existe servidor disponível para ligação remota.


## Estado do serviço SSH
O serviço SSH não está instalado ou não está disponível neste ambiente (systemd não encontrou ssh.service).

## Endereço identificado
192.168.1.103 

## Comando de ligação
ssh utilizador@endereco_ip

## Resultado obtido
Foi possível usar o cliente SSH, mas não existe serviço SSH ativo neste sistema para testes de ligação.

## Limitações encontradas
O ambiente utilizado não possui o servidor SSH instalado, pelo que não foi possível testar acesso remoto real.
