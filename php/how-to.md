
Exibir erros
------------

Altere o php.ini. Utilize seu editor preferido, utilizei o "nano";

Localização do arquivo no Fedora:
	
	# nano /etc/php.ini

Localização do arquivo no Ubunto:

	# nano /etc/php5/apache2/php.ini


Procure pelas linhas abaixo e altere os valores como se segue:

	error_reporting = E_ALL
	display_errors = On
	track_errors = On
	html_errors = On

Reinicie o apache:

	(fedora)# systemctl restart httpd.service

	(ubuntu)# /etc/init.d/apache2 restart
