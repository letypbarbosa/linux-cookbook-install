Receitas de instalações de programas no Linux
===

Sabe como instalar aquele programa em determinada distro?
Então, é isso o que esse projeto se destina.


Esquema geral
---

1. Os programas devem ser da área de TI, ex.:


2. Cada pasta deve refletir o programa para instalação e
NÂO precisa da versão do programa, apenas o nome, ex.:

	root/
		php/  		--> linguagem PHP
		mysql/		--> banco de dados mysql
		nano/		--> editor de texto
	

3. Dentro de cada pasta de programa, haverá um arquivo para cada distro, ex:

	root/
		virtual-box/
			fedora.md
			ubuntu.md
			debian.md
		netbeans/
			fedora.md
			ubuntu.md
		file-zilla/
			centos.txt
			debian.txt
		nautilus-rabbit/
			debian.txt
			



4. A linha de comando será sempre precedida do sinal de sharp #.
5. Os comentários serão textos simples e NÂO devem possuir qualquer sinal de comentários (docblock, //, #, etc..)
6. Utilize o [markdown](http://daringfireball.net/projects/markdown/syntax).
7. DENTRO DO ARQUIVO DEVEMOS MENCIONAR A VERSÃO DA DISTRO.
8. Os textos explicativos devem ser bem redigidos, simples e objetivos.




### about.md

Quando quizer descrever o aplicativo utilize o arquivo *about.md*


### how-to.md

Quando quizer criar receitas (básicas) para o aplicativo utilize o arquivo "how-to.md"
