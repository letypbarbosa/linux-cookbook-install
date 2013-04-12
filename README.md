Receitas de instalações de programas no Linux
===

Sabe como instalar aquele programa em determinada distro?
Então, é isso o que esse projeto se destina.


Os programas devem ser da área de TI, ex.:

* linguagem de programação
* banco de dados
* editores de código
* manuais
* etc..


Cada pasta deve refletir o programa para instalação e
NÂO precisa da versão do programa, apenas o nome, ex.:

	root/
		php/  		--> linguagem PHP
		mysql/		--> banco de dados mysql
		nano/		--> editor de texto
	

Dentro de cada pasta de programa, haverá um arquivo para cada distro, ex:

	root/
		virtual-box/
			fedora.txt
			ubuntu.txt
			debian.txt
		netbeans/
			fedora.txt
			ubuntu.txt
		file-zilla/
			centos.txt
			debian.txt
		nautilus-rabbit/
			debian.txt
			

Dentro de cada arquivo há dois tipos de informação: as linhas de comandos e os comentários.

A linha de comando será sempre precedida do sinal de sharp #.
Os comentários serão textos simples e NÂO devem possuir qualquer sinal de comentários (docblock, //, #, etc..)

Imagine como seria a instalação do aplicativo "x-debug" no Ubuntu 12.10.

A localização seria a seguinte:

	root/
		/x-debug/
			ubuntu.txt
		
E o arquivo seria assim:
		

	Dica: talves seja muito mais fácil instalar pelo Software-center, caso não consiga...

	No Ubuntu 12.10, instale os seguintes pacotes:
	# apt-get install php5-dev php-pear

	Com o PECL (pear) pode-se instalar novos pacotes no estilo apt-get.
	Instale o x-debug
	# pecl install xdebug

	Agora é preciso atualizar o arquivo "php.ini" com a inclusão da extensão x-debug.
	Precisamos saber aonde está a extensão, execute:
	# find/ -name 'x-debug.sos'2> /dev/null

	O sistema lhe mostra o caminho, anote-o.

	Abra o arquivo 'php.ini ( /etc/php5/apache2/php.ini ) e 
	no final do arquivo ou na seção de extensões, inclua a seguinte linha:
	Zend_extension="/usr/lib/php5/caminho-anotado"

	Reinicie o apache
	# /etc/init.d/apache2 restart



*DENTRO DO ARQUIVO DEVEMOS MENCIONAR A VERSÃO DA DISTRO*.

Se preferir pode utilizar o [markdown](http://daringfireball.net/projects/markdown/syntax).

Os textos explicativos devem ser bem redigidos, simples e objetivos.
