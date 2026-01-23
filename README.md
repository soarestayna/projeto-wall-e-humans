# Projeto WALL-E: Segurança e Vulnerabilidades em Agentes de IA

### Parceria: EBAC & Semantix (Projeto Prático)

Este projeto consiste em uma investigação técnica sobre os riscos de segurança associados à implementação de Agentes de IA Autônomos, 
focando no conceito de **"Hiper-Conveniência"** e como a busca por automação extrema pode abrir brechas para ataques cibernéticos modernos.

---

## Estrutura do Repositório
* **`/data`**: Documentação das fontes de dados utilizadas via Kaggle (MPDD, AI Governance, Fraud).
* **`/docs`**: Documentação técnica detalhada (Storytelling, LGPD, Glossário e Referências).
* **`/results`**: Relatórios de insights estratégicos e visualizações de dados.
* **`/scripts`**: Notebooks Python com análise exploratória (EDA) e modelos de Machine Learning.
* **`/estudos_complementares`**: Registro das formações que fundamentam o projeto.

---

## Visão Geral do Projeto
O objetivo principal foi analisar como Agentes de IA (como o WALL-E da Humans) interagem com dados sensíveis e quais são os vetores de 
ataque mais comuns em grandes modelos de linguagem (LLMs), como a **Injeção de Prompt (Prompt Injection)**.

### Vetores de Ataque Investigados
* **Prompt Injection:** Como instruções maliciosas podem "sequestrar" o comportamento da IA para contornar filtros de segurança.
* **Vazamento de Dados (Data Leakage):** Riscos de exposição de informações sensíveis contidas no treinamento ou na memória de curto prazo do agente.
* **Hiper-Conveniência vs. Segurança:** A análise do trade-off onde a facilidade de uso do usuário final acaba reduzindo as camadas de autenticação e verificação.

---

## Tecnologias e Metodologias
* **Análise de Dados (EBAC):** Base para manipulação de datasets e modelagem estatística.
* **Análise de Redes Complexas (USP):** Estudo da propagação de ameaças e identificação de hubs críticos em infraestruturas interconectadas.
* **Cibersegurança (Cisco/OWASP):** Frameworks de segurança (OWASP Top 10 for LLMs) e monitoramento de logs para identificação de anomalias.

---

## Lógica de Triagem e Inteligência de Ameaças (CTI)

Para garantir que o analista humano receba dados prontos para a tomada de decisão, o sistema categoriza os alertas conforme a tabela abaixo:

| Tipo de Ameaça | Técnica Provável | Nível de Perigo | Ação do Sistema |
| :--- | :--- | :--- | :--- |
| **Prompt Injection** | Jailbreak (DAN) | Crítico | Bloqueio imediato e Alerta SOC |
| **Data Leakage** | Exfiltração via API | Alto | Suspensão de token e Revisão Humana |
| **Anomalia de Consumo**| Automação Excessive| Médio | Flag para análise de comportamento |
| **Prompt Seguro** | Interação Normal | Baixo | Autorizado |

---

## Visão Estratégica e Conclusões

**O Equilíbrio entre Escala e Confiança:** A análise exploratória revelou que, embora modelos de ML possam identificar a vasta maioria das tentativas 
de injeção de prompt, o risco residual de erro é inaceitável para transações financeiras autônomas.

A solução proposta neste projeto não é a automação total, mas a **Triagem Assistida (Human-in-the-Loop)**. O "Vigia" reduz a carga de trabalho do SOC ao 
filtrar o ruído massivo, permitindo que o analista humano foque apenas nos casos de alta complexidade. 


---

## Documentação Detalhada
Acesse os capítulos para entender a fundamentação teórica completa:
1. [Introdução e Storytelling: O Paradoxo WALL-E](docs/01-storytelling.md)
2. [Privacidade e LGPD: Transparência e Dados](docs/02-privacidade-lgpd.md)
3. [Riscos Residuais e Futuro: O Desafio Poliglota](docs/03-limitacoes-futuro.md)
4. [Glossário Técnico de Cibersegurança](docs/04-glossario.md)
5. [Referências Éticas e Bibliografia](docs/05-creditos-referencias.md)

---

## Autora
* **Tayná Soares** - [LinkedIn](https://www.linkedin.com/in/tayna-soares-4394ba150)
* Formação em Analista de Dados (EBAC) e Cibersegurança (Cisco).
