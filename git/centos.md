Instalar a versão 1.8.3 do git
----

Download dos arquivos:

	# Http://git-core.googlecode.com/files/git-1.8.3.4.tar.gz wget - See more at: http://translate.googleusercontent.com/translate_c?depth=1&hl=pt-BR&prev=/search%3Fq%3Dhttp://www.unixmen.com/how-to-install-latest-git-on-rhel-6-centos-6/%26client%3Dfirefox-a%26hs%3DNes%26rls%3Dorg.mozilla:en-US:official&rurl=translate.google.com.br&sl=en&u=http://www.unixmen.com/how-to-install-latest-git-on-rhel-6-centos-6/&usg=ALkJrhiZWABtbkYJqkoaPsTuqhHDOvBSMA#sthash.WTw4oOr7.dpuf
        # Wget-O git-manpages-1.8.3.4.tar.gz http://code.google.com/p/git-core/downloads/detail?name=git-manpages-1.8.3.4.tar.gz&can=2&q = - See more at: http://translate.googleusercontent.com/translate_c?depth=1&hl=pt-BR&prev=/search%3Fq%3Dhttp://www.unixmen.com/how-to-install-latest-git-on-rhel-6-centos-6/%26client%3Dfirefox-a%26hs%3DNes%26rls%3Dorg.mozilla:en-US:official&rurl=translate.google.com.br&sl=en&u=http://www.unixmen.com/how-to-install-latest-git-on-rhel-6-centos-6/&usg=ALkJrhiZWABtbkYJqkoaPsTuqhHDOvBSMA#sthash.WTw4oOr7.dpuf

Instalar a bibliotecas necessárias:
        
        # yum instalar zlib-devel perl-CPAN gettext

Realizar a instalação:
    
        # Tar xvfz git-1.8.3.4.tar.gz
        # Cd git-1.8.3.4
        # / Configure
        # Make
        # Sudo make prefix = / usr install
        # Git - version


Referências 
---------
http://www.unixmen.com/how-to-install-latest-git-on-rhel-6-centos-6/ 
http://halyph.blogspot.com.br/2013/08/how-to-install-git-1834-on-centos-64.html
