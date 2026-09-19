<img src="assets/profile/hero.svg" width="100%" alt="Daniel Souza — Software · Product · AI Engineering. Uma informação atravessa três portões em sequência: afirmado, verificado e decidido.">

**Construo sistemas que separam o que foi afirmado, o que foi verificado e o que foi decidido — do problema real ao produto testado.**

Venho da operação — marketplace, CRM e indicadores — e por isso começo pelo problema, não pela tecnologia. Trabalho da modelagem e da arquitetura até a implementação, os testes e a experiência do produto, com dados e IA aplicada onde eles ajudam a decidir.

## Projetos em destaque

<a href="https://github.com/danielsouzaa7/pulse-marketplace-decision-intelligence"><img src="assets/projects/pulse.svg" width="100%" alt="Pulse: a média da empresa fica dentro da faixa esperada enquanto a zona 7 sai dela; o motor marca a anomalia e ordena as prioridades, e o LLM recebe apenas a evidência para narrar."></a>

### Pulse — Marketplace Decision Intelligence

Transforma os sinais dispersos de um marketplace em uma lista curta de decisões priorizadas, cada uma com a evidência que a sustenta.

- **Problema:** na média da empresa, a zona que está falhando desaparece; olhando métrica por métrica, são sinais demais para agir.
- **Diferencial:** o motor decide, o LLM só narra. Números, prioridades e recomendações saem de funções determinísticas, e um validador confere cada número da resposta do modelo contra a evidência.
- **Prova:** 656 testes (655 passam; 1 pulado, documentado), sobre dados 100% sintéticos.
- **Stack:** Python · DuckDB · SQL · pandas · Streamlit · Anthropic SDK
- **Status:** em construção incremental, sem implantação em produção.

**[Abrir o repositório](https://github.com/danielsouzaa7/pulse-marketplace-decision-intelligence)**

<br>

<a href="https://github.com/danielsouzaa7/event-operations-os-showcase"><img src="assets/projects/event-operations.svg" width="100%" alt="Event Operations OS: três fatos acendem em sequência — confirmou, declarou e recebido — e depois se separam: são fatos distintos, e nenhum vira o outro sem verificação."></a>

### Event Operations OS

Sistema para casas de eventos pagos: convidados, RSVP, Pix, check-in na porta, mesas e fechamento financeiro versionado.

- **Problema:** WhatsApp, planilha, lista e extrato divergem — e "confirmou" vira "pagou" sem ninguém ter visto o dinheiro.
- **Diferencial:** regras críticas dentro do PostgreSQL — idempotência, locks de linha e fechamento imutável, que ganha uma nova versão quando chega um Pix atrasado.
- **Prova:** 1.137 testes unitários; integração e aceitação contra PostgreSQL e PostgREST reais.
- **Stack:** Next.js · React · TypeScript · PostgreSQL
- **Status:** software comercial — código privado, apresentação pública.

**[Abrir o showcase](https://github.com/danielsouzaa7/event-operations-os-showcase)**

<sub>Também no GitHub: [VeloFin](https://github.com/danielsouzaa7/velofin-fintech), MVP acadêmico de gestão financeira em HTML e Tailwind CSS. Projetos de clientes ficam em repositórios privados.</sub>

## Como eu construo

<img src="assets/profile/workflow.svg" width="100%" alt="Problema, regras, arquitetura, código, testes e produto, em sequência. Quando o problema pede IA, um ramo sai da arquitetura, passa por dados, modelo e decisão, e volta para os testes.">

Não começo pela tecnologia. Começo pelo problema — e pelos estados que não podem se confundir.

1. **Problema** — o que acontece na operação real, inclusive quando dá errado.
2. **Regras** — quais fatos são distintos e quais invariantes nunca podem quebrar.
3. **Arquitetura** — onde cada regra precisa morar para continuar verdadeira sob concorrência e falha.
4. **Código** — o mínimo que sustenta as regras.
5. **Testes** — contra dependências reais quando o risco está nelas.
6. **Produto** — telas que mostram a diferença entre os estados, em vez de escondê-la.

Quando o problema envolve dados e IA, o caminho ganha um ramo: **dados → modelo → decisão**. A IA fica dentro de uma fronteira verificável — ela explica; quem decide é o sistema ou uma pessoa — e esse ramo também passa pelos testes.

## Stack

**Engenharia** — TypeScript · React · Next.js · PostgreSQL · Supabase · Python · Vitest · pytest

**Dados** — SQL · pandas · DuckDB · Parquet · Streamlit · Power BI

**IA aplicada** — Anthropic SDK · LLM restrito à evidência · validação das respostas contra dados estruturados

## Contato

Veja os projetos acima ou fale comigo no [LinkedIn](https://www.linkedin.com/in/danielsouzavalerio).
