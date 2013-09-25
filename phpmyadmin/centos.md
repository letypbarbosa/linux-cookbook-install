CENTOS 6.4

Instalar o software:

    # yum install php-mysql -y   


Baixe e instale o repositório EPEL primeiro:

    # wget http://dl.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
    # rpm -ivh EPEL-release-6-8.noarch.rpm 


Instale o software:

    # yum install phpmyadmin -y 


Abra o arquivo phpmyadmin para configurar este:

    #  nano /etc/httpd/conf.d/phpMyAdmin.conf

Comente o seguinte trecho:

    # <Directory
    # <IfModule Mod_authz_core.c>
    # # Apache 2.4
    # <RequireAny>
    # Exigir ip 127.0.0.1
    # Exigir ip :: 1
    # </ RequireAny>
    # </ IfModule>
    # <IfModule !mod_authz_core.c>
    # # Apache 2.2
    # Order Deny, Permitir
    # Deny from all
    # Allow from 127.0.0.1
    # Permitir que a partir :: 1
    # </ IfModule>
    # </ Directory> 

Reinicie o serviço Apache.

    # /etc/init.d/httpd restart 
