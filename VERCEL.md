# Publicar na Vercel

Este projeto é uma aplicação React + Vite estática, configurada para a Vercel.

## Configuração

- Comando de build: `npm run build:vercel`
- Diretório de saída: `dist/public`
- Framework: Vite
- Não é necessário backend para executar a avaliação.

## Publicação

1. Importe este projeto na Vercel.
2. Mantenha o diretório raiz como a pasta que contém `package.json`.
3. Use as configurações detectadas pelo `vercel.json`.
4. Clique em **Deploy**.

## Domínio personalizado

Depois que o deploy funcionar, abra **Settings → Domains**, adicione o domínio e siga os registros DNS apresentados pela Vercel.
