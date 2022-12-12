# Download_Cylance
Repositório de instaladores do Cylance para Download via script de instalação. 

# Configurações no Código
Deve ser adicionado no código os seguintes paramêtros:

* userLocal = '' #Nome de usuário com permissões de administrador no sistema
* pwdLocal = ''  #Senha de acesso do perfil administrador
* pidKey = ''    #Chave de licença do cliente

# Compilando em .exe

Para compilar o código em um arquivo .exe você primeiramente precisa realizar a instalação do serviço PyInstaller com o comando:
  
  ip install pyinstaller
  
Realize o download do arquivo icone oficial diposnível neste repositório: drop.ico

Em seguida execute o comando para compilar

  pyinstaller -F --icon-dropico CyInstall.py

Este comando deve ser executado em uma pasta raíz do sistema (não em um diretório do One Drive por exemplo)
