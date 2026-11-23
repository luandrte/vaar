# Onde o site vai ficar no ar

> **Em linguagem simples:** um site precisa "morar" em algum computador ligado na internet. Há duas
> opções: o **GitHub Pages** (grátis, direto deste repositório) ou o **Dokploy** na VPS do VAAR
> (o servidor alugado na Hostinger, que só será montado na Fase 3). Ainda não foi decidido.

## O risco do GitHub Pages

- As regras do GitHub Pages parecem **proibir usar o serviço principalmente para um negócio online,
  comércio eletrônico ou SaaS comercial** [não confirmado — em 23/11/2026 a rede desta sessão bloqueou
  o acesso a <https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits>,
  a página oficial que trata disso].
- Se for assim, uma página de apresentação simples (sem login, sem venda) **talvez** possa ficar no Pages,
  mas o site do jogador (com conta e compra de vídeos) não deve.

## A alternativa: Dokploy

- O site pode rodar no Dokploy, na mesma VPS da Hostinger do resto do sistema (DEC-002).
- Vantagem: sem o risco das regras do Pages e tudo num só lugar.
- Desvantagem: depende da VPS, que só existe a partir da Fase 3.

## O que falta

- **Q-001** (no `vaar-sistema`, `docs/questoes-abertas.md`): GitHub Pages ou Dokploy?
  Sugestão: Pages só para uma página de apresentação enquanto a VPS não existe; Dokploy quando houver
  login ou venda.
- **T-002**: confirmar a regra na página oficial do GitHub.
