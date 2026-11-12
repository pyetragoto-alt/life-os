# LIFE OS

Aplicativo pessoal de organização com interface em português.

## Arquivos
- `index.html`: entrada do aplicativo.
- `manifest.webmanifest`: metadados para instalação como aplicativo.
- `icon.svg`: ícone.
- `sw.js`: service worker para cache e suporte offline.

## Publicar com GitHub Pages
O repositório está configurado como privado. Para disponibilizar o app por um endereço web:
1. Abra **Settings → Pages**.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
4. Aguarde o GitHub publicar e use o endereço exibido na própria tela Pages.

## Dados
A versão atual utiliza armazenamento local do navegador. Os dados não são sincronizados automaticamente entre dispositivos; limpar os dados do navegador pode apagá-los. O service worker permite armazenar os arquivos do app em cache, mas não cria sincronização em nuvem.

## Instalação no Chrome
Depois que o site estiver publicado e aberto por HTTPS, use o ícone **Instalar** na barra de endereço do Chrome (ou o menu ⋮ → Transmitir, salvar e compartilhar → Instalar página como app, conforme a versão do navegador).
