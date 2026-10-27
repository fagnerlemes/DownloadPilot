# DownloadPilot

Gerenciador de downloads para Windows, com organização de arquivos e extensão para Microsoft Edge e Google Chrome. **By Fagner Lemes.**

**[Baixar DownloadPilot 0.1.9 para Windows x64](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.9/DownloadPilot-Setup-0.1.9.exe)** · [Todas as versões](https://github.com/fagnerlemes/DownloadPilot/releases)

## Downloads

| Versão | Instalador completo | Atualização incremental | Extensão |
| --- | --- | --- | --- |
| **[0.1.9 — atual](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v0.1.9)** | [Baixar EXE](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.9/DownloadPilot-Setup-0.1.9.exe) | [0.1.8 → 0.1.9](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.9/DownloadPilot-Patch-0.1.8-para-0.1.9.exe) | [ZIP · 0.1.8](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.9/DownloadPilot-Extensao-0.1.8.zip) |
| [0.1.6](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v0.1.6) | [Baixar EXE](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.6/DownloadPilot-Setup-0.1.6.exe) | [0.1.5 → 0.1.6](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.6/DownloadPilot-Patch-0.1.5-para-0.1.6.exe) | [ZIP](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.6/DownloadPilot-Extensao-0.1.6.zip) |
| [0.1.3](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v0.1.3) | [Baixar EXE](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.3/DownloadPilot-Setup-0.1.3.exe) | [0.1.2 → 0.1.3](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.3/DownloadPilot-Patch-0.1.2-para-0.1.3.exe) | [ZIP](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.3/DownloadPilot-Extensao-0.1.3.zip) |
| [0.1.2](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v0.1.2) | [Baixar EXE](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.2/DownloadPilot-Setup-0.1.2.exe) | [0.1.0 → 0.1.2](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.2/DownloadPilot-Patch-0.1.0-para-0.1.2.exe) | [ZIP](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.2/DownloadPilot-Extensao-0.1.2.zip) |
| [0.1.0 — lançamento](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v0.1.0) | [Baixar EXE](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.0/DownloadPilot-Setup-0.1.0.exe) | — | [ZIP](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.0/DownloadPilot-Extensao-0.1.0.zip) |

Os pacotes são para Windows x64. O instalador inclui os componentes necessários para executar o aplicativo. Cada release traz os hashes em `SHA256SUMS.txt`.

## Instalar ou atualizar

- **Primeira instalação:** execute o instalador completo da versão atual.
- **Já usa a 0.1.8:** use o patch 0.1.8 → 0.1.9.
- **Usa outra versão anterior, incluindo 0.1.6:** use o instalador completo 0.1.9; não precisa passar pelas versões intermediárias.
- Antes de atualizar, escolha **Sair** no ícone do DownloadPilot perto do relógio. Fechar a janela pode apenas minimizá-la para a bandeja.

O histórico, as preferências e os arquivos baixados são preservados. Não é necessário executar o instalador completo e o patch para a mesma atualização.

## O que o programa faz

- Gerencia downloads de arquivos de qualquer tipo, com fila, progresso, pausa e retomada quando o servidor permite.
- Usa até quatro conexões por arquivo em servidores compatíveis.
- Sugere pastas por categoria e permite uma subpasta personalizada.
- Abre a pasta do download e seleciona o arquivo no Explorador.
- Pode assumir downloads do navegador acima do tamanho configurado, como 50 MB.
- Oferece captura de vídeo e áudio como funções adicionais do gerenciador, além de imagens/carrosséis por links individuais compatíveis.
- Converte áudios diretos para MP3 quando você marca a opção em Novo download, um arquivo por vez; o formato original permanece padrão.
- Permite baixar a capa de vídeos do Instagram como JPG quando disponível e conectar opcionalmente a sessão do Instagram pela extensão.
- Permite limpar registros concluídos e com erro de uma só vez, sem apagar os arquivos ou remover downloads pendentes.
- Ao receber um link pela extensão, abre somente Novo download em primeiro plano e mantém o gerenciador na bandeja.
- Continua os downloads na bandeja e pode iniciar minimizado com o Windows.
- Mostra o uso de até três discos; clicar no disco oferece abrir a unidade no Explorador.
- Inclui transparência com desfoque nativo do Windows, com maior contraste entre os elementos.

Pausa, retomada, conexões simultâneas e captura dependem do servidor e do endereço. Downloads que exigem sessão/cookies podem continuar no navegador. Não há suporte a DRM; não existe garantia de captura em qualquer site.

## Extensão para Edge, Chrome e Brave

A extensão acompanha o programa. Ainda é instalada localmente, pelo modo de desenvolvedor; não está publicada nas lojas.

1. Instale o DownloadPilot e abra **Extensão** no aplicativo.
2. No Edge, abra `edge://extensions`; no Chrome, `chrome://extensions`.
3. Ative **Modo de desenvolvedor** e escolha **Carregar sem compactação**.
4. Selecione `%LOCALAPPDATA%\Programs\DownloadPilot\extension`.
5. Confira a conexão pelo ícone da extensão e atualize as páginas abertas.

O ZIP disponível nos releases precisa ser extraído antes de carregar. Prefira a pasta fixa do aplicativo, que é atualizada pelos patches. A versão atual do aplicativo usa a extensão 0.1.8. Se sua extensão for mais antiga, recarregue-a na página de extensões depois de atualizar o programa e recarregue as páginas abertas. Quem já usa a extensão 0.1.8 não precisa recarregá-la apenas para habilitar a conversão para MP3.

Para captura automática por tamanho, habilite a opção nas configurações do aplicativo e **Permitir captura de downloads** no popup da extensão. Cada parte de um arquivo entra como um download separado; o programa não junta os ZIPs gerados pelo Google Drive.

No popup da extensão, **Pop-ups nas páginas** permite ocultar apenas os botões flutuantes. Detecção, envio pelo ícone e captura de downloads continuam funcionando.

A versão 0.1.6 aprimora a identificação de vídeos em diversos sites. Use a extensão na página ou cole o link em **Novo download**. A disponibilidade depende do player e do acesso ao conteúdo.

## Converter áudios para MP3

Ao receber um arquivo de áudio direto, marque **Salvar áudio como MP3** em **Novo download**. Se o endereço não tiver extensão, use **Verificar link** para identificar o arquivo. A conversão acontece depois do download e mostra o estado **Convertendo para MP3**. Pausar interrompe a conversão; **Iniciar / retomar** tenta novamente usando as partes baixadas. O arquivo final respeita a pasta escolhida e recebe um número no nome se já existir. Converter não melhora a qualidade do áudio original.

Para vídeos e publicações, use a opção existente **Somente áudio · MP3** no seletor de qualidade.

## Instagram: sessão opcional e capas

Para uma publicação que exija login, abra o Instagram em uma janela normal do navegador, entre na conta que tem acesso ao conteúdo e use **Conectar Instagram** no ícone da extensão. A permissão de cookies é opcional. A sessão é protegida localmente para o usuário do Windows, expira em até 12 horas e pode ser desconectada pela extensão ou pelas configurações do aplicativo. Não garante acesso a todos os conteúdos ou verificações adicionais do site.

Após verificar um vídeo do Instagram, escolha **Capa do Reel · imagem JPG** em **Qualidade e formato** para baixar somente a capa fornecida pelo site, quando disponível. Vídeo continua sendo a seleção padrão.

## Histórico

- **0.1.9:** conversão opcional de áudios diretos para MP3 após baixar, fila de conversão, pausa e nova tentativa com partes preservadas.
- **0.1.8 (distribuição local; incluída na 0.1.9):** sessão opcional do Instagram, capas de vídeos em JPG e mensagens de falha sem seletor de qualidade vazio.
- **0.1.7 (distribuição local; incluída na 0.1.9):** remove o registro cancelado da captura confirmada no navegador, preservando os demais registros.
- **0.1.6:** identificação de vídeos aprimorada em diversos sites, limpeza coletiva do histórico, captura com somente Novo download em primeiro plano e abertura das unidades do carrossel.
- **0.1.5 (distribuição local; incluída na 0.1.6):** atualização do link ao navegar entre Pins, links individuais do Facebook, correção de Abrir pasta e contraste do acrílico.
- **0.1.4 (distribuição local; incluída na 0.1.6):** links individuais do Instagram/Pinterest, fotos e carrosséis, opção de ocultar os botões flutuantes.
- **0.1.3:** transparência real do fundo externo com desfoque nativo do Windows, opção para desligar e fundo opaco de compatibilidade.
- **0.1.2:** revisão visual, pesquisa identificada, assinatura, informações do programa, tamanho de janela persistente, gráfico de discos e botão para abrir pasta.
- **0.1.0:** base de lançamento com instalador, extensão, captura por tamanho, mídia, organização por pastas, bandeja e inicialização com Windows.

O acrílico requer Windows 11 com suporte ao efeito e transparência habilitada no sistema. O aplicativo mantém um fundo opaco quando o efeito não está disponível.

## Componentes e suporte

Este repositório reúne os pacotes de distribuição e sua documentação. Os componentes externos mantêm suas licenças: consulte [avisos, versões e fontes](THIRD-PARTY-NOTICES.md).

Contato: **fagner.lemes@gmail.com**.
