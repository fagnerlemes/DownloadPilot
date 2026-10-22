# DownloadPilot

Gerenciador de downloads para Windows, com organização de arquivos e extensão para Microsoft Edge e Google Chrome. **By Fagner Lemes.**

**[Baixar DownloadPilot 0.1.3 para Windows x64](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.3/DownloadPilot-Setup-0.1.3.exe)** · [Todas as versões](https://github.com/fagnerlemes/DownloadPilot/releases)

## Downloads

| Versão | Instalador completo | Atualização incremental | Extensão |
| --- | --- | --- | --- |
| **[0.1.3 — atual](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v0.1.3)** | [Baixar EXE](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.3/DownloadPilot-Setup-0.1.3.exe) | [0.1.2 → 0.1.3](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.3/DownloadPilot-Patch-0.1.2-para-0.1.3.exe) | [ZIP](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.3/DownloadPilot-Extensao-0.1.3.zip) |
| [0.1.2](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v0.1.2) | [Baixar EXE](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.2/DownloadPilot-Setup-0.1.2.exe) | [0.1.0 → 0.1.2](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.2/DownloadPilot-Patch-0.1.0-para-0.1.2.exe) | [ZIP](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.2/DownloadPilot-Extensao-0.1.2.zip) |
| [0.1.0 — lançamento](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v0.1.0) | [Baixar EXE](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.0/DownloadPilot-Setup-0.1.0.exe) | — | [ZIP](https://github.com/fagnerlemes/DownloadPilot/releases/download/v0.1.0/DownloadPilot-Extensao-0.1.0.zip) |

Os pacotes são para Windows x64. O instalador inclui os componentes necessários para executar o aplicativo. Cada release traz os hashes em `SHA256SUMS.txt`.

## Instalar ou atualizar

- **Primeira instalação:** execute o instalador completo da versão atual.
- **Já usa a 0.1.2:** use o patch 0.1.2 → 0.1.3.
- **Já usa a 0.1.0:** use o instalador completo atual ou aplique os patches na ordem 0.1.0 → 0.1.2 → 0.1.3.
- Antes de atualizar, escolha **Sair** no ícone do DownloadPilot perto do relógio. Fechar a janela pode apenas minimizá-la para a bandeja.

O histórico, as preferências e os arquivos baixados são preservados. Não é necessário executar o instalador completo e o patch para a mesma atualização.

## O que o programa faz

- Gerencia downloads de arquivos de qualquer tipo, com fila, progresso, pausa e retomada quando o servidor permite.
- Usa até quatro conexões por arquivo em servidores compatíveis.
- Sugere pastas por categoria e permite uma subpasta personalizada.
- Abre a pasta do download e seleciona o arquivo no Explorador.
- Pode assumir downloads do navegador acima do tamanho configurado, como 50 MB.
- Oferece captura de vídeo e áudio como funções adicionais do gerenciador.
- Continua os downloads na bandeja e pode iniciar minimizado com o Windows.
- Mostra o uso de até três discos e inclui transparência com desfoque na 0.1.3.

Pausa, retomada, conexões simultâneas e captura dependem do servidor e do endereço. Downloads que exigem sessão/cookies podem continuar no navegador. Não há suporte a DRM; não existe garantia de captura em qualquer site.

## Extensão para Edge e Chrome

A extensão acompanha o programa. Ainda é instalada localmente, pelo modo de desenvolvedor; não está publicada nas lojas.

1. Instale o DownloadPilot e abra **Extensão** no aplicativo.
2. No Edge, abra `edge://extensions`; no Chrome, `chrome://extensions`.
3. Ative **Modo de desenvolvedor** e escolha **Carregar sem compactação**.
4. Selecione `%LOCALAPPDATA%\Programs\DownloadPilot\extension`.
5. Confira a conexão pelo ícone da extensão e atualize as páginas abertas.

O ZIP disponível nos releases precisa ser extraído antes de carregar. Prefira a pasta fixa do aplicativo, que é atualizada pelos patches. Depois de atualizar o programa, recarregue a extensão na página de extensões.

Para captura automática por tamanho, habilite a opção nas configurações do aplicativo e **Permitir captura de downloads** no popup da extensão. Cada parte de um arquivo entra como um download separado; o programa não junta os ZIPs gerados pelo Google Drive.

## Histórico

- **0.1.3:** transparência real do fundo externo com desfoque nativo do Windows, opção para desligar e fundo opaco de compatibilidade.
- **0.1.2:** revisão visual, pesquisa identificada, assinatura, informações do programa, tamanho de janela persistente, gráfico de discos e botão para abrir pasta.
- **0.1.0:** base de lançamento com instalador, extensão, captura por tamanho, mídia, organização por pastas, bandeja e inicialização com Windows.

O acrílico requer Windows 11 com suporte ao efeito e transparência habilitada no sistema. O aplicativo mantém um fundo opaco quando o efeito não está disponível.

## Componentes e suporte

Este repositório reúne os pacotes de distribuição e sua documentação. Os componentes externos mantêm suas licenças: consulte [avisos, versões e fontes](THIRD-PARTY-NOTICES.md).

Contato: **fagner.lemes@gmail.com**.