## Tutorial de instalação e configuração

Este tutorial tem como finalidade demonstrar a instalação e configuração do i3geo na distribuição.

## Observações gerais sobre a instalação

Os códigos para instalação do i3Geo são compactados em dois arquivos diferentes:

* versão para Linux/windows, que contém apenas os códigos do i3Geo, sendo necessária a criação de um ambiente de funcionamento com Apache, PHP5, Mapserver, etc. Para instalar no Ubuntu, veja aqui um script que pode ajudar e o post Instalação do i3Geo no Ubuntu 12 ou maior. 


* versão windows_ms4w que traz o i3Geo dentro do pacote MS4W . O ms4w é um sistema para Windows que traz o Apache, PHP e Mapserver já instalados, bastando copiar a pasta ms4w para o diretório local (drive c:). Após a cópia, veja o arquivo "c:\ms4w\leia-me.txt" que contém as orientações sobre a inicialização do Apache e do i3geo. Nos casos de "upgrade" de versão do i3Geo, veja o arquivo "guia_de_migracao.txt" existente na pasta "i3geo" ou http://localhost/i3geo/guia_de_migracao.txt. Os arquivos com o i3Geo ficam localizados em c:\ms4w\Apache\htdocs\i3geo.

Esses arquivos estão disponíveis no SVN, que é o sistema utilizado para controle das versões do software e desenvolvimento colaborativo. Ao acessar o svn digite seu login e senha (iguais aos utilizados para acessar o site da comunidade). Importante: após fazer o cadastro na comunidade leva um tempo para que o seu login seja registrado no SVN.

Os arquivos de download não contém o software R, necessário em algumas funções de análise espacial do i3Geo.

Se você já possui o MS4W instalado pode ser necessário sua remoção ou desativação em favor do uso da versão disponibilizada junto com os arquivos do i3Geo. Isso pode ocorrer se a versão do Mapserver que o MS4W já instalado estiver usando não for compatível com a versão mais recente do i3Geo. 


## Configurando o arquivo ms_configura.php

## Configurando o arquivo mapfile de inicialização
