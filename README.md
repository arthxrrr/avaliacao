Criar um emulador no Android Studio

Abra o Android Studio.
Vá até Tools, depois em Device Manager.
Clique em Create Device.
Selecione um modelo de dispositivo (ex: Pixel 4) e clique em Next.
Clique em Finish.

Como habilitar o SDK no Android Studio 

No Android Studio, vá até File, depois em Settings.
Vá para Appearance & Behavior, depois em System Settings, e depois em Android SDK.
Na aba SDK Platforms, marque a versão desejada (ex: Android API 33) e clique em Apply.
A instalação será feita automaticamente. Após finalizar, clique em OK.

Como configurar as variáveis de ambiente no Windows

Pressione "Win + S" e digite "variáveis de ambiente".
Clique em Editar variáveis de ambiente do sistema.
Na janela que abrir, clique em Variáveis de Ambiente.
Em Variáveis do sistema, clique em Novo e adicione:

    Nome da variável: `JAVA_HOME`  
    Valor da variável: `C:\Program Files\Java\jdk-17` (ou o caminho onde o JDK está instalado)

    Nome da variável: `ANDROID_HOME`  
    Valor da variável: `C:\Users\SeuUsuario\AppData\Local\Android\Sdk`

5. Ainda em Variáveis do sistema, encontre a variável "Path", selecione e clique em Editar.
6. Adicione os seguintes caminhos:

   - "%ANDROID_HOME%\platform-tools"  
   - "%ANDROID_HOME%\emulator"

7. Clique em OK para fechar todas as janelas e aplicar as alterações.

Como abrir o projeto no emulador

   Abra o Android Studio.
   Vá em Tools Device Manager.
   Clique no botão de play ao lado do dispositivo criado para iniciar o emulador.
   Abra o terminal no VSCode 
   Digite npm run start
