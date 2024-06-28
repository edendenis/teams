# Como instalar/configurar/usar o `Microsoft Teams` no `Linux Ubuntu`

## Resumo

Neste documento estão contidos os principais comandos e configurações para configurar/instalar/usar o `Microsoft Teams` no `Linux Ubuntu`.

## _Abstract_

_This document contains the main commands and settings for configuring/installing/use the `Microsoft Teams` on `Linux Ubuntu`._

## Descrição [2]

`Microsoft Teams`

O Microsoft Teams é uma plataforma de colaboração e comunicação empresarial desenvolvida pela Microsoft. Ele oferece uma variedade de recursos, incluindo bate-papo em equipe, videoconferência, compartilhamento de arquivos e integração com outras ferramentas e serviços da Microsoft, como o Office 365. O Microsoft Teams permite que equipes de trabalho se comuniquem e colaborem de forma eficiente, independentemente da localização geográfica, facilitando a organização de reuniões virtuais, o compartilhamento de documentos e a colaboração em projetos. Com recursos avançados de segurança e conformidade, integração com aplicativos de terceiros e suporte para uma variedade de dispositivos, o Microsoft Teams é amplamente utilizado por empresas de todos os tamanhos para melhorar a produtividade e a eficiência da equipe.


## 1. Configurar/Instalar o `Microsoft Teams` no Linux` Ubuntu` [1]

Para configurar/instalar o `Microsoft Teams` no `Linux Ubuntu`, você pode seguir estas etapas:

1. Abra o `Terminal Emulator`. Você pode fazer isso pressionando: `Ctrl + Alt + T`


2. Certifique-se de que seu sistema esteja limpo e atualizado.

    2.1 Limpar o `cache` do gerenciador de pacotes `apt`. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo `apt` e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando: `sudo apt clean` 
    
    2.2 Remover pacotes `.deb` antigos ou duplicados do cache local. É útil para liberar espaço, pois remove apenas os pacotes que não podem mais ser baixados (ou seja, versões antigas de pacotes que foram atualizados). Digite o seguinte comando: `sudo apt autoclean`

    2.3 Remover pacotes que foram automaticamente instalados para satisfazer as dependências de outros pacotes e que não são mais necessários. Digite o seguinte comando: `sudo apt autoremove -y`

    2.4 Buscar as atualizações disponíveis para os pacotes que estão instalados em seu sistema. Digite o seguinte comando e pressione `Enter`: `sudo apt update`

    2.5 **Corrigir pacotes quebrados**: Isso atualizará a lista de pacotes disponíveis e tentará corrigir pacotes quebrados ou com dependências ausentes: `sudo apt --fix-broken install`

    2.6 Limpar o `cache` do gerenciador de pacotes `apt`. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo `apt` e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando: `sudo apt clean` 
    
    2.7 Para ver a lista de pacotes a serem atualizados, digite o seguinte comando e pressione `Enter`:  `sudo apt list --upgradable`

    2.8 Realmente atualizar os pacotes instalados para as suas versões mais recentes, com base na última vez que você executou `sudo apt update`. Digite o seguinte comando e pressione `Enter`: `sudo apt full-upgrade -y`
 

Para instalar o `Microsoft Teams` no `Linux Ubuntu`. A Microsoft oferece uma versão do Teams especificamente para Linux, que pode ser baixada e instalada diretamente. Aqui estão os passos básicos para a instalação:

3. **Baixe o pacote `.deb` do `Microsoft Teams`:** Você pode baixar o pacote `.deb` para o `Teams` diretamente do site oficial da Microsoft.

4. **Instale o pacote `.deb`:** Depois de baixar o pacote, você pode instalá-lo usando a linha de comando. Abra um terminal e navegue até o diretório onde o pacote foi baixado. Então, use o comando `dpkg` para instalar o pacote. Por exemplo: `sudo dpkg -i teams_<versao>.deb`

    Substitua <versao> pelo nome do arquivo do pacote que você baixou.

5. **Resolva as dependências:** Se o comando anterior indicar que há dependências não satisfeitas, execute o seguinte comando para corrigir essas dependências: `sudo apt-get install -f`
    
    Este comando instalará as dependências necessárias para o `Microsoft Teams`.

6. **Inicie o `Microsoft Teams`:** Após a instalação, você pode iniciar o `Microsoft Teams` procurando por ele no menu de aplicativos do seu Ubuntu.

Lembre-se de que a Microsoft atualiza o Teams regularmente, então é uma boa ideia manter seu software atualizado. A instalação pelo pacote `.deb` geralmente não configura um repositório para atualizações automáticas, então você pode precisar baixar e instalar manualmente novas versões do Teams para mantê-lo atualizado.


## 1.1 Código completo configurar/instalar

Para configurar/instalar o `Microsoft` no `Linux Ubuntu` sem precisar digitar linha por linha, você pode seguir estas etapas:

1. Abra o `Terminal Emulator`. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Digite o seguinte comando e pressione `Enter`:

    ```
    NÃO há.
    ```

2. Certifique-se de que seu sistema esteja limpo e atualizado.

    2.1 Limpar o `cache` do gerenciador de pacotes `apt`. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo `apt` e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando: `sudo apt clean` 
    
    2.2 Remover pacotes `.deb` antigos ou duplicados do cache local. É útil para liberar espaço, pois remove apenas os pacotes que não podem mais ser baixados (ou seja, versões antigas de pacotes que foram atualizados). Digite o seguinte comando: `sudo apt autoclean`

    2.3 Remover pacotes que foram automaticamente instalados para satisfazer as dependências de outros pacotes e que não são mais necessários. Digite o seguinte comando: `sudo apt autoremove -y`

    2.4 Buscar as atualizações disponíveis para os pacotes que estão instalados em seu sistema. Digite o seguinte comando e pressione `Enter`: `sudo apt update`

    2.5 **Corrigir pacotes quebrados**: Isso atualizará a lista de pacotes disponíveis e tentará corrigir pacotes quebrados ou com dependências ausentes: `sudo apt --fix-broken install`

    2.6 Limpar o `cache` do gerenciador de pacotes `apt`. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo `apt` e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando: `sudo apt clean` 
    
    2.7 Para ver a lista de pacotes a serem atualizados, digite o seguinte comando e pressione `Enter`:  `sudo apt list --upgradable`

    2.8 Realmente atualizar os pacotes instalados para as suas versões mais recentes, com base na última vez que você executou `sudo apt update`. Digite o seguinte comando e pressione `Enter`: `sudo apt full-upgrade -y`
 

## Referências

[1] OPENAI. ***Instale o Teams no Ubuntu.*** Disponível em: <https://chat.openai.com/c/a21756a6-1a1d-4945-a183-9bd9b7ed3ef9> (texto adaptado). Acessado em: 07/02/2024 21:01.

[2] OPENAI. ***Vs code: editor popular.*** Disponível em: <https://chat.openai.com/c/b640a25d-f8e3-4922-8a3b-ed74a2657e42> (texto adaptado). Acessado em: 07/02/2024 21:01.

