<picture><source media="(max-width: 600px)" srcset="https://github.com/danielsouzaa7/danielsouzaa7/raw/main/assets/profile/hero-mobile.svg"><img src="assets/profile/hero.svg" width="100%" alt="Daniel Souza — Dados, Business Intelligence e IA aplicada. Sinais de marketplace, CRM e operação convergem para dados, passam por análise e se dividem em decisão, software e produto."></picture>

**Dados & Business Intelligence · Analytics · Marketplace · IA aplicada · Engenharia de software e produto.**

Começo pela decisão que o negócio precisa tomar — e só depois escolho entre dados, software ou IA para sustentá-la.

## Da operação para a engenharia

<picture><source media="(max-width: 600px)" srcset="https://github.com/danielsouzaa7/danielsouzaa7/raw/main/assets/profile/marketplace-mobile.svg"><img src="assets/profile/marketplace.svg" width="100%" alt="Pedidos chegam e percorrem a operação, viram métricas, depois insights e finalmente sistemas. Mais de R$ 1,1 milhão em vendas e mais de 5 mil pedidos."></picture>

Venho da operação — marketplace, CRM e indicadores. Estruturei e conduzi a operação de marketplace de uma concessionária Honda — anúncios, pós-venda, indicadores, prevenção de fraude — da implantação até **R$ 1,1 milhão+ em vendas e mais de 5 mil pedidos**.

Foi ali que a pergunta deixou de ser *"quanto vendemos?"* e passou a ser *"por que vendemos isso, e o que fazer na semana que vem?"*. É por isso que começo pela decisão: primeiro entendo o que o negócio precisa decidir, depois desenho os dados e o sistema que sustentam essa decisão. Os projetos abaixo nasceram dessa pergunta.

## Projetos em destaque

<a href="https://github.com/danielsouzaa7/analista-dados-ia"><picture><source media="(max-width: 600px)" srcset="https://github.com/danielsouzaa7/danielsouzaa7/raw/main/assets/projects/analista-dados-ia-mobile.svg"><img src="assets/projects/analista-dados-ia.svg" width="100%" alt="Analista de dados com IA: uma pergunta é digitada, o agente monta o plano e escreve o SQL no servidor; um pacote com o código e os dados cruza a fronteira e o Python roda no navegador de quem perguntou, calculando a correlação; por fim aparece o selo números conferidos."></picture></a>

### Analista de dados com IA

Quem tem dados mas não sabe SQL nem Python pergunta em português e recebe a resposta com o gráfico, cada passo à vista.

- **Problema:** quem tem dados mas não sabe SQL nem Python depende de um analista para cada pergunta.
- **Diferencial:** o agente pensa no servidor, e o Python gerado pela IA roda no navegador de quem pergunta, num Worker sem rede além do caminho fixo do Pyodide. Cada passo aparece ao vivo, com tempo e custo.
- **Prova:** avaliação contra o modelo real publicada com a meta não batida (média de 7,0/8 em 5 rodadas, meta de 8/8); 5 rodadas de red team, cada achado corrigido com teste ou publicado como risco aceito; 10 vetores de fuga bloqueados, testados em 3 navegadores.
- **Stack:** Python · FastAPI · DuckDB · Gemini (API compatível com OpenAI) · Pyodide em Web Worker · SSE · ECharts · pytest · Playwright
- **Status:** [no ar](https://analista-dados-ia.onrender.com) no Render grátis (dorme após uns 15 min sem uso e leva cerca de um minuto para acordar).

**[Abrir o repositório](https://github.com/danielsouzaa7/analista-dados-ia)**

<a href="https://github.com/danielsouzaa7/pulse-marketplace-decision-intelligence"><picture><source media="(max-width: 600px)" srcset="https://github.com/danielsouzaa7/danielsouzaa7/raw/main/assets/projects/pulse-mobile.svg"><img src="assets/projects/pulse.svg" width="100%" alt="Pulse: a média da empresa fica dentro da faixa esperada enquanto a zona 7 sai dela; o motor detecta, diagnostica, prioriza e monta a evidência, e só depois dessa fronteira o modelo de linguagem escreve a explicação."></picture></a>

### Pulse — Marketplace Decision Intelligence

Transforma os sinais dispersos de um marketplace em uma lista curta de decisões priorizadas, cada uma com a evidência que a sustenta.

- **Problema:** na média da empresa, a zona que está falhando desaparece; olhando métrica por métrica, são sinais demais para agir.
- **Diferencial:** o motor decide, o modelo explica. Métricas, anomalias, impacto e a ordem das prioridades saem de funções determinísticas; o modelo de linguagem recebe só a evidência já calculada, e um validador confere cada número da resposta contra ela.
- **Prova:** 656 testes (655 passam; 1 pulado, documentado), sobre dados 100% sintéticos.
- **Stack:** Python · DuckDB · SQL · pandas · Streamlit · Anthropic SDK
- **Status:** em construção incremental, sem implantação em produção.

**[Abrir o repositório](https://github.com/danielsouzaa7/pulse-marketplace-decision-intelligence)**

<a href="https://github.com/danielsouzaa7/event-operations-os-showcase"><picture><source media="(max-width: 600px)" srcset="https://github.com/danielsouzaa7/danielsouzaa7/raw/main/assets/projects/event-operations-mobile.svg"><img src="assets/projects/event-operations.svg" width="100%" alt="Event Operations OS: confirmou, declarou e recebido aparecem ligados e depois se separam; em seguida o fechamento v1 é gravado, chega um Pix atrasado e nasce o v2, com a v1 intacta."></picture></a>

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

<picture><source media="(max-width: 600px)" srcset="https://github.com/danielsouzaa7/danielsouzaa7/raw/main/assets/profile/workflow-mobile.svg"><img src="assets/profile/workflow.svg" width="100%" alt="Problema, operação, dados, regras, arquitetura, implementação, validação e produto, em sequência; dos dados saem dois ramos opcionais, BI e Analytics e IA e automação, que voltam para a validação."></picture>

Não começo pela tecnologia. Começo pelo problema — e pelos fatos que não podem se confundir.

1. **Problema** — qual decisão o negócio precisa tomar, e com que frequência.
2. **Operação** — como isso acontece na vida real, inclusive quando dá errado.
3. **Dados** — o que existe, o que falta e o que não é confiável.
4. **Regras** — quais fatos são distintos e quais invariantes nunca podem quebrar.
5. **Arquitetura** — onde cada regra precisa morar para continuar verdadeira sob concorrência e falha.
6. **Implementação** — o mínimo que sustenta as regras.
7. **Validação** — testes contra dependências reais quando o risco está nelas.
8. **Produto** — telas que mostram a diferença entre os estados, em vez de escondê-la.

Quando o problema pede análise, os dados abrem um ramo de **BI e Analytics**; quando pede automação, um ramo de **IA aplicada**. Os dois voltam para a validação antes de virar produto — inclusive a IA, que explica e sugere, mas não decide sozinha.

## Stack

Escolho a ferramenta depois de entender o problema — ela é consequência dele, não o contrário.

<picture><source media="(max-width: 600px)" srcset="https://github.com/danielsouzaa7/danielsouzaa7/raw/main/assets/profile/stack-icons-mobile.svg"><img src="assets/profile/stack-icons.svg" width="100%" alt="Ferramentas por grupo — Dados e BI: Python, SQL, Power BI, DuckDB, pandas. Engenharia: TypeScript, JavaScript, React, Next.js, PostgreSQL, Supabase, Git. IA aplicada: Anthropic SDK e validação de saída."></picture>

**Dados & BI** — SQL · Power BI · Python · pandas · DuckDB

**Engenharia** — TypeScript · JavaScript · React · Next.js · PostgreSQL · Supabase · Git

**IA aplicada** — LLMs · Anthropic SDK · workflows · validação de saída contra dados estruturados

## Engenharia que eu consigo provar

<picture><source media="(max-width: 600px)" srcset="https://github.com/danielsouzaa7/danielsouzaa7/raw/main/assets/profile/evidence-mobile.svg"><img src="assets/profile/evidence.svg" width="100%" alt="Placas de evidência: Analista de dados com IA com 713 testes passando no CI público, 97% de cobertura, avaliação contra o modelo real com média 7,0 de 8 em 5 rodadas (meta 8 de 8 não batida), 10 vetores de fuga bloqueados em 3 navegadores e 5 rodadas de red team; Pulse com 656 testes, 655 passam e 1 pulado documentado; Event Operations OS com 1.137 de 1.137 unitários, 649 de 649 migrations, 50 de 50 integração, 25 de 25 aceitação e concorrência aprovada."></picture>

Números de suítes que rodam, cada um do seu projeto — sem somar um no outro. Os números do Analista de dados com IA vêm do CI público no GitHub Actions, conferível por qualquer pessoa. As suítes de integração e aceitação do Event Operations OS rodam contra PostgreSQL e PostgREST reais, em laboratório local descartável.

## Contato

<img src="assets/profile/footer.svg" width="100%" alt="Um sinal atravessa dados, decisão e produto.">

Quer conversar sobre dados, analytics, IA aplicada ou software? Me chame no **[LinkedIn](https://www.linkedin.com/in/danielsouzavalerio)** — ou comece pelos projetos acima.

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielsouzaa7/danielsouzaa7/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielsouzaa7/danielsouzaa7/output/snake-light.svg">
  <img src="https://raw.githubusercontent.com/danielsouzaa7/danielsouzaa7/output/snake-dark.svg" width="100%" alt="Animação da grade de contribuições do GitHub">
</picture>
