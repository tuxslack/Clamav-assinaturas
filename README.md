# Clamav-assinaturas

Arquivo com várias assinaturas de banco de dados, Sanesecurity, Maldet, Bofhland, Foxhole, Rfxn, Malware.expert, etc.
Ao executar o freshclam o programa tentará buscar uma atualização no endereço especificado na linha DatabaseMirror, caso não encontre, ele passará para o endereço subsequente, até encontrar e baixar as atualizações.
Depois ele executará todas as DatabaseCustomURL.
Deixe o arquivo com as configurações abaixo (está completo com espelhos de todo lugar para malware, spam, phishing, etc).
O arquivo em si ficou gigantesco, mas cada atualização completa demora em média 2 a 3 minutos dependendo do seu PC e da sua banda de internet.

pluma /etc/clamav/freshclam.conf  <<< usei o pluma use teu editor de texto preferido.

WARNING
"The mirrors reserve the right to block your IP address, if you are downloading too many times per hour or are
abusing their servers/bandwidth in any way."

AVISO
"Os espelhos e links se reservam o direito de bloquear seu IP caso você abusar dos downloads e atualizações muitas vezes por hora ou abusar do servidor de qualquer maneira."
Faça atualizações dos bancos de dados e assinaturas com sensatez.



Fontes:

https://plus.diolinux.com.br/t/transforme-o-clamav-no-melhor-antivirus-para-linux-melhor-que-pago/53245
https://www.vivaolinux.com.br/etc/freshclamconf/
