Ajustando o DocumentRoot no Fedora
----------------------------------

Eu não consegui alterar o local, então 
optei por dar permissão de escrita e alterar o dono das pastas.

Mudar o dono da pastas /var/www/html de root para o seu usuário:
	
	# cd /var/www/
	# chowner seu_usuario:seu_usuario html/ -R


Alterando as permissões:

	# chmod 777 -R html/
	


Ajustando o DocumentRoot no Ubuntu
----------------------------------

No Ubuntu eu já consigo trocar o local.

Altere o arquivo "default" no seguinte local:

	# nano /etc/apache2/sites-available/default

Eu utilizei o "nano" como editor de textos.

Procure entender o arquivo e altere o caminho para:

	/home/usuario/NetBeansProjects

... o exemplo acima condiz com meu HD, obviamente você deve
escolher a pasta que faz sentido no seu HD.


Reinicie apache

	# /etc/init.d/apache2 restart
