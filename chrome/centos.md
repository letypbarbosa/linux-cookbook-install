CHROME


Adicione ao repositório o chrome. Para isoo cire o seguite arquivo

	/etc/yum.repos.d/google-chrome.repo

.. com o seguinte conteúdo

	[google-chrome]
	name=google-chrome
	baseurl=http://dl.google.com/linux/chrome/rpm/stable/$basearch
	enabled=1
	gpgcheck=1
	gpgkey=https://dl-ssl.google.com/linux/linux_signing_key.pub


Agora instale:

	# yum install google-chrome-stable


E então instale o pacote:

	# Chmod u + x install_chrome.sh

        # . / Install_chrome.sh
