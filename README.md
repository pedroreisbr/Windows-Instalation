Windows-Instalation
===================

#Processo de configuração da maquina pessoal Windows 8.1

- Alteração dos diretórios de arquivos do usuário (profile) para K:\Profile
    * algumas pastas não tinham permissão, com isso é necessário setar o `ADM` como proprietário e dar permissão de controle total pros arquivos
        * `$ *takeown /F <PASTA> /R /D Y*`
        * `$ *icacls <PASTA> /grant:r ADM:F /T*`

- Alteração das variaveis ** REGEDIT **: onde continha ** C:\ ** foi alterado para ** K:\ **

    * *Hkey_Local_Machine\Software\Microsoft\Windows\CurrentVersion*
        * $ *ProgramFilesDir*
        * $ *CommonFilesDir*
        * $ *ProgramFilesDir (x86)*
        * $ *CommonFilesDir (x86)*
        * $ *ProgramW6432sDir*
        * $ *CommonW6432Dir*

- Instalar navegadores (firefox e chrome)

    * Instalar complementos
        * Download Them All
        
- Instalar Drivers 64
    * Vídeo Intel (15.33.30.64.3958)
    * Nvidia 660M
    * Wireless Killer
    * Bluetooth (automático, fn + F12)
    * Webcam (automático, fn + F10)
    * Driver Leitor Cartão
    * Driver Audio
    * Driver Leitor Biometrico (KeepSafe)

- Instalar Winrar


    

  
