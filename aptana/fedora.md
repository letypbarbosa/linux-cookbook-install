Fedora 18, Aptana



Realize o download do Aptana por meio do site e extraia na pasta home
	
	# www.aptana.org/products/studio3/download 

Mova a pasta extraida para o usr/local/bin e acesse este

	# mv Aptana_Studio_3 /usr/local/bin/


Incluir o aptana dir:

	#nano ~/.bashrc 
	#PATH=$PATH:/usr/local/bin/Aptana_Studio_3 

Adicione o ícone:

	#cd /usr/share/applications 

Crie um novo arquivo:

	#nano aptana-studio-3.desktop 

Adicione no arquivo:

	[Desktop Entry] Name=Aptana Studio 3 Exec=/usr/local/bin/Aptana_Studio_3/aptana Icon=/usr/local/bin/Aptana_Studio_3/icon.xpm 	      	Type=Application Categories=Development 


Fonte:

* http://stackoverflow.com/questions/10607534/aptana-studio-3-install-using-yum









