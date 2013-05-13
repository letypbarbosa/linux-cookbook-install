FEDORA 17+


Instalar o software:

    # yum install httpd


Colocar o apache para iniciar junto com o sistema operacional:

    # chkconfig --levels 235 httpd on
    

Iniciar o serviço:

    # systemctl start httpd.service


Para testar, abra o navegador e acesse http://localhost
uma página intitulada "Fedora Test Page" será exibida.
