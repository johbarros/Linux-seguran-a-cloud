# Backup e Recuperação

## Ficheiro crítico identificado

Foi selecionado o ficheiro:

/var/www/html/index.html

Este ficheiro corresponde à página principal do servidor Apache.

## Criação do backup

Comando utilizado:

sudo cp /var/www/html/index.html backup/

Resultado:

O ficheiro foi copiado com sucesso para a pasta de backup.

## Recuperação

Foi criada uma pasta de teste para validar a recuperação:

mkdir teste

O ficheiro foi restaurado através do comando:

cp backup/index.html teste/

## Validação

Foi verificado o conteúdo da pasta de teste utilizando:

ls teste

Também foi confirmada a existência do conteúdo do ficheiro através de:

cat teste/index.html

## Conclusão

O backup foi criado com sucesso e a recuperação foi realizada corretamente, demonstrando que o ficheiro pode ser restaurado quando necessário.
