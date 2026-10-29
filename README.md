# DownloadPilot

Gerenciador de downloads para Windows, com organização de arquivos e extensão para Microsoft Edge e Google Chrome. **By Fagner Lemes.**

**Primeira versão oficial completa: 1.0.0.**

**[Baixar DownloadPilot 1.0.0 para Windows x64](https://github.com/fagnerlemes/DownloadPilot/releases/download/v1.0.0/DownloadPilot-Setup-1.0.0.exe)** · [Notas da versão](https://github.com/fagnerlemes/DownloadPilot/releases/tag/v1.0.0)

## Instalar ou atualizar

| Situação | Arquivo |
| --- | --- |
| Nova instalação ou qualquer versão anterior | [Instalador completo 1.0.0](https://github.com/fagnerlemes/DownloadPilot/releases/download/v1.0.0/DownloadPilot-Setup-1.0.0.exe) |
| Já usa a versão 0.1.9 | [Patch 0.1.9 → 1.0.0](https://github.com/fagnerlemes/DownloadPilot/releases/download/v1.0.0/DownloadPilot-Patch-0.1.9-para-1.0.0.exe) |
| Extensão para instalação local | [ZIP da extensão 0.1.8](https://github.com/fagnerlemes/DownloadPilot/releases/download/v1.0.0/DownloadPilot-Extensao-0.1.8.zip) |

Antes de instalar manualmente, escolha **Sair** no ícone do DownloadPilot perto do relógio. Fechar a janela pode apenas minimizá-la para a bandeja. Não é necessário desinstalar a versão anterior nem executar o instalador completo e o patch para a mesma atualização.

Histórico, preferências e arquivos baixados são preservados. O instalador completo permite atualizar diretamente de versões antigas, sem passar pelas intermediárias. Os pacotes são para Windows x64 e incluem os componentes necessários. Os hashes estão em [SHA256SUMS.txt](https://github.com/fagnerlemes/DownloadPilot/releases/download/v1.0.0/SHA256SUMS.txt).

## Atualizações pelo aplicativo

A primeira instalação da **1.0.0 é manual**. Depois, use **Verificar atualizações** no rodapé ou nas Configurações. A consulta diária vem ativada e pode ser desligada.

Quando houver uma versão nova, o aplicativo mostra novidades, tamanho e tipo de pacote. Você escolhe quando baixar e instalar. O programa usa um patch apenas se a versão e os arquivos instalados corresponderem à base; nos demais casos, usa o instalador completo.

O atualizador verifica assinatura, tamanho e SHA256. Downloads ativos só são pausados com sua confirmação. O aplicativo salva o estado, fecha e reabre após a instalação. Uma cópia dos arquivos anteriores permite a recuperação se a instalação ou a conferência final falhar.

A assinatura interna protege o canal de atualização e não substitui um certificado de editor do Windows; avisos de reputação do SmartScreen podem continuar aparecendo.

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

O ZIP disponível nos releases precisa ser extraído antes de carregar. Prefira a pasta fixa do aplicativo, que é atualizada pelos patches. A versão atual do aplicativo usa a extensão 0.1.8. Se sua extensão for mais antiga, recarregue-a na página de extensões depois de atualizar o programa e recarregue as páginas abertas. Quem já usa a extensão 0.1.8 na pasta fixa não precisa reinstalá-la para esta versão. Aplicativo e extensão têm numeração independente.

Para captura automática por tamanho, habilite a opção nas configurações do aplicativo e **Permitir captura de downloads** no popup da extensão. Cada parte de um arquivo entra como um download separado; o programa não junta os ZIPs gerados pelo Google Drive.

No popup da extensão, **Pop-ups nas páginas** permite ocultar apenas os botões flutuantes. Detecção, envio pelo ícone e captura de downloads continuam funcionando.

O DownloadPilot inclui identificação de vídeos aprimorada em diversos sites. Use a extensão na página ou cole o link em **Novo download**. A disponibilidade depende do player e do acesso ao conteúdo.

## Converter áudios para MP3

Ao receber um arquivo de áudio direto, marque **Salvar áudio como MP3** em **Novo download**. Se o endereço não tiver extensão, use **Verificar link** para identificar o arquivo. A conversão acontece depois do download e mostra o estado **Convertendo para MP3**. Pausar interrompe a conversão; **Iniciar / retomar** tenta novamente usando as partes baixadas. O arquivo final respeita a pasta escolhida e recebe um número no nome se já existir. Converter não melhora a qualidade do áudio original.

Para vídeos e publicações, use a opção existente **Somente áudio · MP3** no seletor de qualidade.

## Instagram: sessão opcional e capas

Para uma publicação que exija login, abra o Instagram em uma janela normal do navegador, entre na conta que tem acesso ao conteúdo e use **Conectar Instagram** no ícone da extensão. A permissão de cookies é opcional. A sessão é protegida localmente para o usuário do Windows, expira em até 12 horas e pode ser desconectada pela extensão ou pelas configurações do aplicativo. Não garante acesso a todos os conteúdos ou verificações adicionais do site.

Após verificar um vídeo do Instagram, escolha **Capa do Reel · imagem JPG** em **Qualidade e formato** para baixar somente a capa fornecida pelo site, quando disponível. Vídeo continua sendo a seleção padrão.

## Histórico do projeto

A 1.0.0 consolida as versões de desenvolvimento 0.1.x. A evolução está registrada no [histórico resumido](HISTORICO.md).

O acrílico requer Windows 11 com suporte ao efeito e transparência habilitada no sistema. O aplicativo mantém um fundo opaco quando o efeito não está disponível.

## Componentes e suporte

Este repositório reúne os pacotes de distribuição e sua documentação. Os componentes externos mantêm suas licenças: consulte [avisos, versões e fontes](THIRD-PARTY-NOTICES.md).

Contato: **fagner.lemes@gmail.com**.
