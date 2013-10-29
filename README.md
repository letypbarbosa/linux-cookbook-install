Receitas de instalações de programas no Linux
===

Sabe como instalar aquele programa em determinada distro?

Então, é isso o que esse projeto se destina.


Esquema geral
---


Estrutura de arquivos:

(não colocar a versão no nome das pastas)

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

1. Os textos explicativos devem ser bem redigidos, simples e objetivos.
2. Utilize o [markdown](http://daringfireball.net/projects/markdown/syntax).
3. Dentro dos arquivos devemos mencionar a versão da distro.
4. Quando quizer descrever o aplicativo utilize o arquivo *about.md*
5. Quando quizer criar receitas (básicas) para o aplicativo utilize o arquivo *how-to.md*
6. Linhas de comando será sempre precedida do sinal de sharp #.
7. Os comentários serão textos simples e NÂO devem possuir qualquer sinal de comentários (docblock, //, #, etc..)
