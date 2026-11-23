# CLAUDE.md — convenções do projeto VAAR (repositório `vaar`, público)

> **Em linguagem simples:** este arquivo é o "manual da casa" do repositório **público** do VAAR.
> Aqui fica **só o site público**. Qualquer pessoa na internet pode ver tudo o que está aqui.
> O dono do projeto, Luan, está começando na programação: tudo precisa ser explicado sem jargão.

## Regra número um: nada interno aqui

- **Nenhuma** senha, token, chave de API, endereço de servidor interno ou dado de usuário.
- **Nenhum** documento interno: decisões, questões, pesquisas, SQL, workflows do n8n e o software da
  quadra ficam no repositório **privado** `luandrte/vaar-sistema`.
- Na dúvida, o arquivo vai para o `vaar-sistema`.

## Regras de trabalho

1. Toda entrega é um **pull request (PR) em português**, pequeno e fácil de ler, seguindo o modelo
   em [`.github/pull_request_template.md`](.github/pull_request_template.md).
   A descrição começa com duas ou três linhas simples dizendo o que o PR faz e por que importa.
2. **Ninguém faz push nem Merge na `main`.** Quem faz o Merge é o dono, depois da revisão.
3. Mudança que toca os dois repositórios vira **um par de PRs**, com a ordem do Merge escrita nos dois.
4. Se uma sessão de trabalho reiniciar, confira o que já está no disco e nos PRs abertos antes de continuar.
5. **Nunca invente número.** Todo número no site (preço, prazo, estatística) precisa ter fonte ou ter
   sido decidido pelo dono.
6. Datas e dias da semana são gerados a partir da data, nunca escritos à mão.

## Decisões e questões

- As decisões (`DEC-NNN`) e as questões (`Q-NNN`) do projeto ficam **no `vaar-sistema`**
  (`docs/decisoes.md` e `docs/questoes-abertas.md`), mesmo quando o assunto é o site.
  Um PR aqui que aplica uma decisão faz par com o PR do `vaar-sistema` que a registra.
- Cada fase tem uma Issue de índice ("Fase N — índice") no `vaar-sistema`.

## Diagramas

- Em **Mermaid**, dentro do Markdown, testados com `mmdc` antes do PR.

## Hospedagem

- Ver [`docs/hospedagem.md`](docs/hospedagem.md): o GitHub Pages pode não permitir um site de negócio
  online; a alternativa é o Dokploy (questão Q-001 no `vaar-sistema`).

## Para quem escreve

- O dono é iniciante: **toda descrição de PR e todo LEIA-ME começam em linguagem simples**.
- Palavras técnicas ficam explicadas no glossário do `vaar-sistema` (`docs/glossario.md`).
