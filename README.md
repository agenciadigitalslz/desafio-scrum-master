# 📝 Resenha Crítica – *“Agile Project Development at Intel: A Scrum Odyssey”*

> Estudo de caso real da adoção de Scrum em 12 times da Intel no setor de engenharia de testes de microprocessadores.

---

## 🎯 Visão Geral do Case

Em um cenário dominado pela cultura waterfall e marcado por alta rotatividade, entregas com prazos estourados e comunicação truncada entre times, a Intel decidiu implementar o framework Scrum em sua divisão de Product Development Engineering (PDE). A iniciativa nasceu de um desejo legítimo de resgatar o controle sobre o processo de desenvolvimento e melhorar a qualidade de vida e a previsibilidade das entregas.

Com mais de 50 profissionais distribuídos em sete equipes funcionais, a jornada Scrum foi estruturada em três fases principais:

1. **Fase 1 – Preparação para o silício:** Treinamentos intensivos, pilotos com times voluntários, planejamento da mudança e alinhamento estratégico.
2. **Fase 2 – Sobrevivendo ao silício:** Momento de crise, com exigência extrema sobre os times, que responderam adaptando os rituais do Scrum a ciclos diários.
3. **Fase 3 – Produção em larga escala:** Consolidação da prática ágil e surgimento de estruturas de feature teams multifuncionais.

---

## 🧩 Elementos-Chave da Implementação

| Elemento | Destaque |
|---------|----------|
| **Papéis** | Scrum Masters voluntários sem conflito de interesse; Product Owners vindos da liderança funcional |
| **Ferramenta** | XPlanner customizado ("XPlanner2") e posteriormente uma ferramenta própria da Intel |
| **Definição de Pronto (DoD)** | Conjunto rigoroso de critérios que exigia verificação com o PO via “Pair Review” |
| **Cadência** | Sprints de 9 dias, com folga nos finais de semana alternados |
| **Escalabilidade** | De 7 para 18 times, com apoio de coaching externo e reuniões intertimes semanais |
| **Métricas** | Adds, Saves e Escapes permitiram identificar bugs e ambiguidade de requisitos |

---

## 🚨 Lições Aprendidas

### Pontos Fortes (+)
- **Inspeção diária visualizada no burndown**, melhorando a previsibilidade.
- **Times protegidos contra interrupções externas** graças à métrica do “sprint interrupt tax”.
- **Senso de propriedade e orgulho** despertado pelo planejamento baseado em capacidade real (velocity).
- **Auto-organização incentivada** com liberdade gradual para adaptar processos.

### Desvios e Desafios (-)
- POs com dupla função (liderança funcional) **minaram a autonomia dos times**.
- Apenas um Scrum Master no início, acumulando papel em sete times, **sobrecarregando o facilitador**.
- A ferramenta caseira demandava **alto esforço de manutenção**, competindo com o tempo de entrega.

---

## 📈 Impactos e Resultados

| Resultado | Evidência |
|----------|----------|
| **Redução do ciclo de desenvolvimento** | 66% menor comparado aos ciclos anteriores |
| **Maior previsibilidade** | Planejamento com base em velocity, revisado a cada Sprint |
| **Melhoria da moral** | Equipes mais satisfeitas e engajadas, redução de turnover |
| **Cultura organizacional transformada** | Feedback frequente, adaptação contínua e transparência |

> *"O time com pior moral tornou-se o mais produtivo ao final do segundo ano da transição."*

---

## 💡 Recomendações para Novos Scrum Masters

1. **Inicie o processo com fidelidade ao Scrum Guide** por ao menos três meses antes de adaptar.
2. **Incentive o uso de métricas simples**, mas poderosas, como Adds e Escapes.
3. **Evite conflito de interesses em papéis**, separando liderança funcional dos papéis Scrum.
4. **Forme comunidades de prática** entre SMs e POs para apoiar a escalabilidade.
5. **Mostre valor com dados**: ciclo reduzido, menos retrabalho, satisfação crescente.

> *Scrum é sobre construir produtos, mas também sobre reconstruir confiança, foco e colaboração.*

---

## ✨ Conclusão

O case da Intel mostra que é possível implementar Scrum em um ambiente complexo, técnico e resistente a mudanças – desde que haja comprometimento com o aprendizado, apoio da liderança e abertura para adaptar-se à realidade do time.

Mais que uma adoção de framework, o que ocorreu na Intel foi uma transformação comportamental, em que a cultura da transparência, da experimentação e da inspeção/adaptação passou a fazer parte do DNA da organização.

---

> *“Scrum é menos sobre cerimônias e mais sobre cultivar aprendizado coletivo.”*


---

# 📚 Guia Rápido de Scrum

Este guia é um complemento direto à resenha acima, oferecendo um resumo didático dos principais elementos do **Scrum Guide 2020**, reforçando a prática com teoria.

---

## 🔑 Pilares & Valores do Scrum  

| **PILARES** | **VALORES** |
|-------------|-------------|
| 🟢 **Transparência** | 🤝 **Compromisso** |
| 🔍 **Inspeção** | 🎯 **Foco** |
| 🔄 **Adaptação** | 🌐 **Abertura** |
|  | 🙌 **Respeito** |
|  | 🦁 **Coragem** |

---

## 🏗️ Cascata x Scrum

| | **Modelo Cascata (Waterfall)** | **Modelo Ágil (Scrum)** |
|---|---|---|
| **Fluxo** | Fases sequenciais | Iterativo & incremental |
| **Planejamento** | Único e fixo | Por Sprint |
| **Entrega de Valor** | Final do projeto | Contínua |

---

## 👥 Papéis e Responsabilidades

| Papel | Responsabilidade | Foco |
|------|------------------|------|
| **Product Owner** | Prioriza o backlog e comunica a Meta do Produto | O *que* será entregue |
| **Scrum Master** | Facilita o processo, remove impedimentos | Como o time trabalha |
| **Developers** | Criam o incremento de valor | Construção do produto |

---

## ⏲️ Eventos do Scrum

| Evento | Timebox | Propósito |
|--------|---------|-----------|
| **Sprint** | ≤ 1 mês | Contêiner para todos os eventos e entrega de valor |
| **Sprint Planning** | ≤ 8h | Define Meta da Sprint e plano de execução |
| **Daily Scrum** | 15min | Inspeção diária e replanejamento |
| **Sprint Review** | ≤ 4h | Apresentar e inspecionar o incremento com stakeholders |
| **Sprint Retrospective** | ≤ 3h | Melhorar processo, pessoas e práticas |

---

## 📦 Artefatos e Compromissos

| Artefato | Compromisso | Finalidade |
|----------|-------------|------------|
| **Product Backlog** | 🎯 Meta do Produto | Lista de tudo que pode ser entregue |
| **Sprint Backlog** | 🥅 Meta da Sprint | Plano detalhado da Sprint |
| **Incremento** | ✅ Definição de Pronto | Conjunto de entregas potencialmente utilizáveis |

---

## 📊 Métricas Essenciais

- **Velocity:** capacidade de entrega por Sprint
- **Burn-down Chart:** visualização do trabalho restante
- **Sprint Goal Success Rate:** índice de metas atingidas

---

## 📘 Leitura Recomendada

- [Scrum Guide 2020 (oficial)](https://scrumguides.org)
- [Case Intel – PDF](http://www.michaeljames.org/Intel-case-study.pdf)
- [Scrum.org](https://scrum.org)
- [Scrum Study Guide – SBOK](https://www.scrumstudy.com/SBOK/SCRUMstudy-SBOK-Guide-2020.pdf)

---

<p align="center"><em>Feito com ❤ e empirismo. Adapte com propósito, inspecione com coragem.</em></p>

---

**👨‍💻 Projeto desenvolvido por [André Lopes](https://www.linkedin.com/in/andre7lopes/)**  
- Estudante de ADS | Foco em Ciência de Dados e Desenvolvimento Web  
- [agenciadigitalslz.com.br](https://www.agenciadigitalslz.com.br)
- [GitHub](https://github.com/agenciadigitalslz)

---
