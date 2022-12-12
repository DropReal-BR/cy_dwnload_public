# Download_Cylance
Repositório de instaladores do Cylance para Download via script de instalação. 

# Configurações no Código
Deve ser adicionado no código os seguintes paramêtros:

* userLocal = '' #Nome de usuário com permissões de administrador no sistema
* pwdLocal = ''  #Senha de acesso do perfil administrador
* pidKey = ''    #Chave de licença do cliente

# Compilando em .exe

  ### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina a biblioteca PyInstaller, para isso no cmd execute o seguinte comando

```bash
  $ ip install pyinstaller
```
Realize o download do arquivo icone oficial disponível neste repositório: drop.ico

Em seguida, para realizar a compilação, execute o seguinte comando
  
```bash
  $ pyinstaller -F --icon-dropico CyInstall.py #Este comando deve ser executado em uma pasta raíz do sistema (não em um diretório do One Drive por exemplo)
```
