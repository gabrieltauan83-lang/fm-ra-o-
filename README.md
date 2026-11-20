# Calculadora de Ração | Fazenda Manjedoura (PWA)

Aplicativo Web Progressivo (PWA) desenvolvido para formulação e cálculo nutricional de rações para bovinos, com suporte offline e comparação com exigências do **BR-CORTE 2023**.

## Arquivos incluídos
- `index.html`: Interface principal, lógica de cálculo, armazenamento local e registro do PWA.
- `manifest.json`: Configurações de instalação do aplicativo (nome, ícones, cores e modo standalone).
- `sw.js`: Service Worker para funcionamento offline.
- `icon-192.png` e `icon-512.png`: Ícones do aplicativo para dispositivos móveis e desktop.

## Como publicar no GitHub Pages
1. Faça upload de todos os arquivos para a raiz do seu repositório no GitHub.
2. Acesse **Settings** > **Pages**.
3. Em **Build and deployment > Source**, selecione **Deploy from a branch**.
4. Escolha a branch `main` (ou `master`), pasta `/ (root)` e clique em **Save**.
5. Aguarde cerca de 1 minuto e acesse a URL gerada para instalar o app no celular ou computador.
