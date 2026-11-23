# Onde o site vai ficar no ar

> **Em linguagem simples:** um site precisa "morar" em algum computador ligado na internet. A decisão
> já foi tomada (**DEC-006**, no repositório `vaar-sistema`): no **GitHub Pages** (grátis, direto deste
> repositório) fica **só uma página de apresentação**, sem login nem venda. Todo o resto vai para o
> **Dokploy**, na VPS do VAAR (o servidor alugado na Hostinger), que será montada na Fase 3.

## A decisão (DEC-006, 23/11/2026)

| O quê | Onde fica | Quando |
| --- | --- | --- |
| Página de apresentação do VAAR (sem login, sem venda) | GitHub Pages, a partir deste repositório | quando a página existir |
| Site do jogador (conta, clipes, compra) | Dokploy, na VPS da Hostinger | Fase 3 |
| Painel da quadra | Dokploy, na VPS da Hostinger | Fase 3 |
| Área do administrador | Dokploy, na VPS da Hostinger | Fase 3 |

## Por que não dá para pôr tudo no GitHub Pages

- A página oficial do GitHub diz que o Pages **não é permitido para rodar negócio online, e-commerce
  ou SaaS comercial** [confirmado — <https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits>,
  acesso em 23/11/2026].
- Por isso a página de apresentação **nunca** pode ganhar login, compra ou área do jogador enquanto
  estiver no Pages. Qualquer uma dessas coisas vai para o Dokploy.

## Histórico

- A pergunta era a **Q-001** (no `vaar-sistema`, `docs/questoes-abertas.md`). O dono aceitou a sugestão
  em 23/11/2026 e ela virou a **DEC-006**.
- A tarefa **T-002** (confirmar a regra na página oficial) foi concluída em 23/11/2026.
