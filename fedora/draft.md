Melhorar o som
http://www.ubuntero.com.br/2011/10/melhorar-qualidade-de-som-de-videos/


yum install openshot
yum install pitivi
Cinerela http://ondalinux.blogs.sapo.cv/6195.html

http://www.hardware.com.br/guias/fedora/multimidia-repositorios-adicionais.html
http://www.vivaolinux.com.br/topico/Iniciantes-no-Linux/Como-saber-a-placa-de-video
http://www.fedora.org.br/fortopic6750.html



Softwares de MP3
----------------

	http://www.abouthack.com/articles/linux/playing-mp3-in-fedora-17.html



Como desabilitar SElinux0
-------------------------

Procure o arquivo "config" na pasta "/etc/selinux/"

	# nano /etc/selinux/config

Altere a linha SELINUX=enable para SELINUX=disabled

Reinicie o linux.

Teste executando:

	# /usr/sbin/getenforce
	Disabled

Veja mais no artigo abaixo:

http://docs.fedoraproject.org/en-US/Fedora/13/html/Security-Enhanced_Linux/sect-Security-Enhanced_Linux-Working_with_SELinux-Enabling_and_Disabling_SELinux.html




Como descobrir qual é a versão do FEDORA
----------------------------------------

	# cat /etc/*release




Como listar todos os usuários
-----------------------------

	# cat /etc/passwd | awk -F ":" '{print $1}'



Como instalar impressora HP
---------------------------

Instale o drive da impressora através do site: http://hplipopensource.com/hplip-web/index.html

Após a conclusão deste, localize o arquivo e execute o seguinte comando:

	# sh hplip-3.12.10a.run

Para mais informações acesse o site: http://hplipopensource.com/hplip-web/install/install/index.html


Adicionar impressora ?
----------------------

	# system-config-printer


Para gerar cd com as atualizações
----------------------------------

	http://revisor.fedoraunity.org/



Qual diretório para scripts de configuração e redirecionamento do apache(.conf) ?
---------------------------------------------------------------------------------

	etc/httpd/conf.d/meuscript.conf


Tudo sobre fedora
-----------------

http://fedora.wiki.br/wiki/FAQ_do_Fedora_10

http://fedoraproject.org/wiki/Administration_Guide_Draft/Apache

http://forums.fedoraforum.org/showthread.php?t=184564

http://www.my-guides.net/en/guides/linux/346-fedora-17-post-installation-guide

http://www.unixmen.com/201205-howto-install-lamp-in-fedora/

http://www.howtoforge.com/installing-apache2-with-php5-and-mysql-support-on-fedora-11-lamp







