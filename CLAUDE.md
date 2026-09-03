# MoodiCare — orientações do projeto

## Fonte de conteúdo

@moodicare.md

`moodicare.md` é a base de conteúdo e a fonte operacional de verdade deste projeto.
`TCC-MOODICARE.pdf` é o material acadêmico original, usado apenas como consulta para
conferir informações essenciais que porventura não estejam no Markdown.

Não altere `moodicare.md`, `TCC-MOODICARE.pdf` nem qualquer outro arquivo de referência.

## O que é este projeto

Este repositório existe para produzir um **case study de Product Design** do MoodiCare,
destinado à publicação no **Behance**. Não é o produto, não é o TCC e não é um app.

### Objetivo do case

Demonstrar pensamento de produto, UX, UI, arquitetura da informação, fluxos, estados,
regras de negócio e decisões visuais. O foco é **design, não implementação**. A
implementação (React Native, Laravel, PostgreSQL) entra apenas como contexto que explica
por que certos estados e funcionalidades eram possíveis.

### Narrativa e senioridade

- A narrativa deve comunicar senioridade **apenas dentro do que está comprovado pelo
  projeto**: pensamento sistêmico, clareza de escopo, ligação entre evidência e decisão,
  domínio de fluxos, estados, regras, arquitetura da informação, UI e handoff.
- Senioridade **não** deve ser simulada por métricas inexistentes, linguagem inflada ou
  afirmações de impacto que o projeto não mediu.

### Limites que não podem ser ultrapassados

- O MoodiCare **não** deve ser apresentado como clinicamente validado.
- **Não** invente métricas, entrevistas, testes de usabilidade, testes de conclusão de
  tarefa, impacto clínico, impacto comportamental, adesão real, retenção ou participação
  não documentada.
- A validação com 65 respondentes foi **exploratória** (interesse declarado e utilidade
  percebida). Não é teste de usabilidade nem validação clínica. O app não foi publicado
  nas lojas nem usado por pessoas externas à equipe.
- Percentuais do formulário devem sair dos números recalculados a partir do CSV
  registrados em `moodicare.md`, sempre com o critério de agrupamento explícito.
- Use formulações como "foi considerado", "foi definido como requisito", "foi projetado
  para" — e não "é acessível", "é seguro", "é eficaz" — salvo quando houver evidência de
  implementação e verificação.

### Como as telas devem aparecer

As telas são **evidências de decisões**, não uma galeria isolada. Cada fluxo ou tela
apresentada precisa estar ligada a uma necessidade, hipótese, requisito, regra, estado ou
aprendizado.

### Regra de sustentação

Cada afirmação importante do case deve estar apoiada por:
1. o conteúdo de `moodicare.md`;
2. os arquivos do projeto; ou
3. uma confirmação posterior da Samantha.

Se nada disso sustentar uma afirmação, não a inclua — pergunte antes.

## Decisões confirmadas pela Samantha

1. **Eixo central da narrativa**: a integração entre acompanhamento medicamentoso,
   monitoramento emocional, calendário integrado e visualização de dados.
2. **Edge cases e comportamentos reais do sistema**: documentados progressivamente, tela a
   tela e fluxo a fluxo, conforme forem analisados. Nunca inventar comportamento ainda não
   confirmado.
3. **Autoria**: apresentar como trabalho individual. Não mencionar orientador,
   colaboradores ou terceiros neste momento.
4. **Ativos visuais** (telas, protótipos, materiais do app): serão enviados
   progressivamente, conforme cada seção do case for desenvolvida.
5. **Personas**: podem ser revisadas e aprimoradas quando a seção correspondente for
   construída.
6. **Evento acadêmico**: mencionar como **Latinoware 2025**.
7. **Números**: apenas os resultados quantitativos mais relevantes entram no case. Cada
   número precisa apoiar uma decisão ou explicar o problema.
8. **Idioma**: o case study é escrito em **inglês** para publicação no Behance. As
   instruções do projeto e os registros internos (este arquivo, `moodicare.md`, memória)
   permanecem em português.
9. **Sequência de trabalho**: não iniciar a implementação de HTML ou CSS até que a
   estrutura narrativa e a referência visual tenham sido analisadas e aprovadas.

## Site do case

O site será, inicialmente, um **case visual simples em HTML e CSS**, com possibilidade de
evolução posterior (mais interatividade, framework, etc.). Não construir a interface até
que a narrativa e a referência visual estejam aprovadas (ver decisão 9 acima).

## Autoria

Autora do projeto: Samantha Manuela Ferri Tavares. Orientador: André Fabiano de Moraes.
Instituto Federal Catarinense — Campus Camboriú, Bacharelado em Sistemas de Informação, 2026.
