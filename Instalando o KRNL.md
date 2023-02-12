# Instalando todos os requisitos para que o KRNL possa funcionar corretamente.

# POR FAVOR, SIGA TODOS OS PASSOS ABAIXO PARA EVITAR ERROS.
1.) Checando se o computador é x64 bits ou x86 bits. Entre no site abaixo e siga os passos que tem no site.

 - [Site](https://www.fca.unesp.br/Home/Instituicao/Administracao/ServicoTec.Informatica/como-saber-se-a-versao-do-windows-e-32-ou-64-bits.pdf)

2.) Após descobrir se seu computador é x64 bits ou x86 bits, vamos instalar os componentes Visual c++ Redistributable.
 - [Visual C++ Redistributable x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)
  - [Visual C++ Redistributable x86](https://aka.ms/vs/16/release/vc_redist.x86.exe)

3.) O seu computador precisa da versão atualizada do [.NET Framework (4.7.2+)](https://dotnet.microsoft.com/download/dotnet-framework/net48) Clique para nessa mensagem em azul para instalar.

4.) Após ter instalado tudo que for necessario, reinicie o seu computador.

**NOTA : O KRNL so funciona no Windows 8.1 pra cima. É necessario ter uma instalação do Windows x64 bits / x86 bits caso você não tenha.**

# Anti-virus Whitelist / Desativando o Anti-virus

**KRNL, igual a qualquer outro exploit é marcado como virus. Isto é conhecido como "Falso positivo", onde o Windows pensa que o arquivo "Krnl.dll" é um virus por causa que é obfuscado, mas você pode ter certeza absoluta de que o KRNL é 100% seguro.

Vamos começar colocando o KRNL na white list do anti-virus do Windows.

1.) Abra as configurações do Windows, e digite "Segurança do windows" e clique em segurança do windows.

2.) Selecione a opção "Proteção contra vírus e ameaças".

3.) Após ter selecionado a opção "Proteção contra vírus e ameaças", clique na opção "Gerenciar configurações" que fica abaixo de "Configurações de proteção contra vírus e ameaças", então desative a opção "Proteção em tempo real".

**(NOTA: SE VOCÊ NÃO QUER FICAR DESATIVANDO A PROTEÇÃO DO SEU WINDOWS QUANDO FOR USAR O KRNL, ENTÃO SIGA OS PASSOS ABAIXO)**

 - Para dar white list ao KRNL, desça 3 opções abaixo de "Proteção em tempo real" e procure pela opção "Exclusões" ou "Adicionar ou remover exclusões" e clique nesta opção.

 - Selecione "Adicionar uma exclusão" e selecione "Pasta". E você vai selecionar a pasta do KRNL ou a pasta em que o KRNL está localizado.

# Instalando : Website

**DEPOIS** de ter completado as etapas anteriores, você está completamente pronto para instalar o KRNL.

O unico site **OFICIAL** do KRNL é https://krnl.place/ , Ao entrar no site, seleciona a opção "Latest Version" que é a mais recomendada, mas você tambem pode escolher a "Legacy Version"
 
 - [Latest Download (Recomendado)](https://k-storage.com/krnl_beta.exe)
 - [Legacy Download](https://k-storage.com/krnl_bootstrapper.exe)
