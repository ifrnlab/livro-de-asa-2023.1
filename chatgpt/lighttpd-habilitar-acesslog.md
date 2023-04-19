# Habilitação de logs no lighttpd

Para habilitar os logs do servidor lighttpd em um servidor Linux, siga os seguintes passos:

1. Abra o arquivo de configuração do lighttpd. O caminho do arquivo pode variar dependendo da distribuição Linux, mas geralmente está localizado em `/etc/lighttpd/lighttpd.conf`.

2. Procure a seção `accesslog` no arquivo de configuração. Ela deve se parecer com isso:

3. Verifique se a linha está comentada. Se estiver, remova o caractere "#" do início da linha para descomentar a configuração.

4. Certifique-se de que o caminho do arquivo de log seja válido e que o usuário do servidor lighttpd tenha permissão de escrita no diretório do arquivo. Neste exemplo, o arquivo de log será criado em `/var/log/lighttpd/access.log`.

5. Salve e feche o arquivo de configuração.

6. Reinicie o servidor lighttpd para que as alterações entrem em vigor. O comando pode variar dependendo da distribuição Linux, mas geralmente é `systemctl restart lighttpd`.

Com essas etapas concluídas, os logs de acesso do servidor lighttpd serão gravados no arquivo de log especificado.

