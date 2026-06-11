# Permissões aplicadas

## Ambiente utilizado
Linux (terminal local)

## Utilizador e grupos
joh

## Ficheiros criados

- publico.txt: ficheiro de acesso público
- restrito.txt: ficheiro com acesso limitado
- script.sh: script executável

## Permissões aplicadas

| Ficheiro     | Permissão | Justificação |
|--------------|----------|--------------|
| publico.txt  | 644      | Pode ser lido por todos, apenas o dono edita |
| restrito.txt | 640      | Apenas dono lê/escreve, grupo pode ler |
| script.sh    | u+x      | Permite execução apenas pelo dono |

## Relação com o princípio do menor privilégio

As permissões foram configuradas para garantir que cada utilizador tem apenas o acesso necessário.
Isto reduz riscos de alteração indevida, leitura não autorizada e execução de ficheiros por terceiros.
