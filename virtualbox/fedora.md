FEDORA 17+


Na pasta atual, crie um arquivo chamado "virtualbox.repo" e insira nele o seguinte conteúdo:
	
	[virtualbox]
	name=Fedora $releasever - $basearch - VirtualBox
	baseurl=http://download.virtualbox.org/virtualbox/rpm/fedora/$releasever/$basearch
	enabled=1
	gpgcheck=1
	gpgkey=http://download.virtualbox.org/virtualbox/debian/oracle_vbox.asc


Mover o arquivo recém criardo para a pasta de repositórios adicionais do Fedora:

	# mv virtualbox.repo /etc/yum.repos.d/

Agora Instale o pacote DMKS executando:

	# yum install dkms

Instalar o Vbox:

	# yum install VirtualBox-4.2


Obs: No meu computador foram exibidas algumas msg de erro que, apesar de não afetar o funcionamento,
eu não soube resolver:
	
	# /var/log/vbox-install.log
	# /var/lib/dkms/vboxhost/4.2.0/bulid/make.log
	# /etc/init.d/vboxdrv setup


Baseado no artigo abaixo

http://www.zealfortechnology.com/2012/06/install-oracle-virtualbox-on-fedora.html

