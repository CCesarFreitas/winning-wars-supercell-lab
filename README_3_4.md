# Winning Wars APP 3.4 — Universal iPhone + Android

## Estrutura que deve ser publicada inteira

app.py
.streamlit/config.toml
static/apple-touch-icon.png
static/favicon.png
static/icon-192.png
static/icon-512.png
static/icon-maskable-512.png
static/manifest.webmanifest

## IMPORTANTE
Não publique somente o app.py. As pastas `.streamlit` e `static` fazem parte
da configuração de instalação.

## iPhone / iPad
1. Publique esta versão.
2. Exclua o atalho Winning Wars antigo da Tela de Início.
3. Feche o Safari.
4. Abra novamente o endereço do app no Safari.
5. Compartilhar > Adicionar à Tela de Início.
6. Se o ícone antigo persistir, limpe os dados desse site no Safari e tente novamente.

## Android
1. Exclua o atalho/app antigo.
2. Abra o Winning Wars no Chrome.
3. Menu ⋮ > Instalar app ou Adicionar à tela inicial.
4. Confirme a instalação.

O icon-maskable-512.png possui margem de segurança para launchers Android que
recortam ícones em círculo, squircle ou quadrado arredondado.
