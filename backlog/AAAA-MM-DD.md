# Backlog — AAAA-MM-DD

<!--
  PADRÃO DECODER — BACKLOG (ver convenção global em ~/.claude/CLAUDE.md)

  - Pasta `backlog/` na raiz do repo, NUNCA commitada — adicionar `backlog/` ao
    .gitignore do projeto na primeira vez que a pasta for criada (já feito neste
    repositório-padrão; copie a linha para o projeto real).
  - Um arquivo Markdown por dia: `backlog/AAAA-MM-DD.md` — contém APENAS o índice.
    Para começar um dia novo, copie este arquivo para `backlog/<data-real>.md`,
    apague a linha de exemplo da tabela, e crie a subpasta do dia (próximo item).
  - Uma subpasta por dia: `backlog/AAAA-MM-DD/` — contém um arquivo por item,
    `backlog/AAAA-MM-DD/<ID>.md`. Copie `AAAA-MM-DD/XX-1.md` como modelo de cada
    item novo. Espelha o mesmo padrão já usado no RTM (`RTM.md` + `rtm/itens/`).
  - ID = prefixo curto da área (defina os prefixos conforme as áreas do projeto,
    ex.: BC = Budget Control, F = Fuel, WH = Weekly Hours) + número sequencial
    (BC-1, BC-2, F-1...). O prefixo nunca reinicia a numeração entre dias — IDs são
    únicos no repositório inteiro, então ao abrir um novo dia confira o último
    número usado por prefixo nos arquivos anteriores.
  - `Done` usa emoji (⬜ pendente, ✅ concluído) — é a única fonte de status de conclusão do item.
  - `Status` é texto livre curto. Valores comuns observados na prática:
      "Backlog"
      "Backlog — causa raiz identificada, falta corrigir"
      "Backlog — investigação em andamento"
      "Backlog — reportado por <pessoa>, investigação em andamento"
      "Em andamento"
      "Concluído"
  - Fonte da verdade: o arquivo em `backlog/AAAA-MM-DD/<ID>.md` manda. O índice
    abaixo é espelho — toda vez que `Done` ou `Status` mudar no arquivo de detalhe,
    a linha correspondente aqui é atualizada na mesma edição, senão os dois
    dessincronizam.
  - Ao identificar bugs a partir de prints/evidências trazidas pelo usuário: registrar
    como item de backlog com causa raiz (se investigada) e referências `arquivo:linha`
    — NÃO implementar a correção sem instrução explícita, a menos que o usuário peça.
-->

Escopo: [opcional — linha curta delimitando o escopo do dia, ex.: "somente módulo X"]

## Índice

| Done | ID | Área | Demanda | Status |
|:---:|----|------|---------|--------|
| ⬜ | [XX-1](AAAA-MM-DD/XX-1.md) | [Área] | [Resumo curto da demanda] | Backlog |
