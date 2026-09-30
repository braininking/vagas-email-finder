# Vagas Email Finder

Buscador de vagas públicas do Themos Vagas com extração de e-mails de candidatura.

## Arquitetura
React + Vite + Cloudflare Worker. O mesmo Worker serve o frontend e a API, sem Render e sem Netlify.

## Rodar
npm install
npm run dev

## Build
npm run build

## Deploy
npx wrangler login
npm run deploy

O projeto usa somente páginas públicas. Não tenta contornar login, CAPTCHA ou outras proteções. O scraper é heurístico porque o HTML do site pode mudar.
