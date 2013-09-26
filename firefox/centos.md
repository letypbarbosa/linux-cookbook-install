Atualizandono CENT OS 6.4
===

...da versão 17 para 24


Adicionar os seguites repositórios:

    # rpm -Uvh http://download.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
    # rpm -Uvh http://rpms.famillecollet.com/enterprise/remi-release-6.rpm



O comando seguite mstra na tela o pacot que poderá ser autalizado

    # yum --enablerepo=remi list firefox


Atualize... 

    # yum update firefox

...ou instale

    # yum install firefox


Fonte

http://www.if-not-true-then-false.com/2011/install-firefox-on-fedora-centos-red-hat-rhel/