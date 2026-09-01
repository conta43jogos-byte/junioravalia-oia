# Publicar na Vercel

Este projeto é uma aplicação React estática e já possui `vercel.json` com o comando e o diretório de saída configurados.

## Publicação pelo GitHub

1. Envie o projeto para um repositório GitHub ou importe o código diretamente pela Vercel.
2. Acesse [vercel.com/new](https://vercel.com/new), entre com sua conta e escolha **Import Git Repository**.
3. Selecione o repositório da avaliação.
4. Confirme as configurações: o comando de build será `pnpm run build:vercel` e o diretório de saída será `dist/public`. Não é necessário adicionar variáveis de ambiente para esta avaliação.
5. Clique em **Deploy**.

## Alterar o domínio

Depois do deploy, abra o projeto na Vercel, entre em **Settings → Domains**, digite o domínio desejado e clique em **Add**. A Vercel mostrará os registros DNS que precisam ser criados no serviço onde o domínio foi comprado. Após a propagação do DNS, o domínio passa a apontar para o site.

Se você ainda não possui domínio, pode usar o endereço gratuito `.vercel.app` criado automaticamente pela Vercel ou comprar um domínio em um registrador de sua preferência.

## Observação sobre as imagens

A imagem da capa usa uma URL pública estável e continua disponível fora do ambiente de desenvolvimento. O projeto não usa banco de dados nem servidor de backend; por isso, a publicação na Vercel funciona como site estático.
