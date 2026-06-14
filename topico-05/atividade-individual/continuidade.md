# Plano de Continuidade Operacional

## Serviço crítico

O serviço crítico identificado é o Apache2, responsável pela disponibilização do website.

## Ficheiros e configurações críticas

* /var/www/html/
* /etc/apache2/apache2.conf
* /etc/apache2/sites-available/
* /etc/apache2/sites-enabled/

Estes ficheiros são essenciais para o funcionamento correto do servidor web.

## Logs importantes

* journalctl -u apache2
* /var/log/apache2/access.log
* /var/log/apache2/error.log

Os logs permitem identificar erros, acessos e problemas de funcionamento.

## Periodicidade de backup

* Backup diário dos ficheiros do website.
* Backup semanal das configurações do Apache.
* Backup adicional antes de alterações importantes.

## Procedimento de recuperação

1. Identificar a falha.
2. Parar o serviço Apache.
3. Restaurar os ficheiros a partir do backup.
4. Restaurar as configurações necessárias.
5. Reiniciar o serviço Apache.
6. Verificar o funcionamento do website.

## Critérios de validação

Após a recuperação deve ser confirmado que:

* O serviço Apache está ativo.
* O website abre normalmente no navegador.
* Não existem erros críticos nos logs.
* Os ficheiros restaurados estão íntegros.

## Conclusão

A existência de backups regulares e de um procedimento de recuperação documentado reduz o impacto de falhas e permite restaurar rapidamente o serviço.
