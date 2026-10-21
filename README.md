# Jin Wei — Dez Bênçãos do Deus da Guerra

Site React + Vite para RPG Murim.

## Rodar localmente

1. Instale Node.js 20+.
2. Execute `npm install`.
3. Execute `npm run dev` e abra o endereço indicado.

## Publicar na Vercel

Envie este projeto para um repositório GitHub e importe-o em https://vercel.com/new . Framework: Vite; build: `npm run build`; pasta de saída: `dist`.

## Sorteio

Usa `crypto.getRandomValues` com rejeição de viés de módulo e Fisher-Yates. A ordem permanece secreta até o desbloqueio e é salva no localStorage do navegador. A sequência é criada por sessão de sorteio e nunca repete bênçãos. Em um novo sorteio, a sequência é substituída. A vida atual define quantas bênçãos estão ativas; bênçãos já reveladas continuam visíveis se a vida for recuperada.
