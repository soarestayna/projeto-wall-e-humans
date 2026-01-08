# Projeto WALL-E: Segurança e Vulnerabilidades em Agentes de IA

### Parceria: EBAC & Semantix (Projeto Prático)

Este projeto consiste em uma investigação técnica sobre os riscos de segurança associados à implementação de Agentes de IA Autônomos, focando no conceito de **"Hiper-Conveniência"** 
e como a busca por automação extrema pode abrir brechas para ataques cibernéticos modernos.

---

## Visão Geral do Projeto
O objetivo principal foi analisar como Agentes de IA (como o WALL-E da Humans) interagem com dados sensíveis e quais são os vetores de ataque mais comuns em grandes modelos 
de linguagem (LLMs), como a **Injeção de Prompt (Prompt Injection)**.

---

## Vetores de Ataque Investigados
Durante o desenvolvimento do estudo, foquei nos seguintes pontos críticos:

* **Prompt Injection:** Como instruções maliciosas podem "sequestrar" o comportamento da IA para contornar filtros de segurança.
* **Vazamento de Dados (Data Leakage):** Riscos de exposição de informações sensíveis contidas no treinamento ou na memória de curto prazo do agente.
* **Hiper-Conveniência vs. Segurança:** A análise do trade-off onde a facilidade de uso do usuário final acaba reduzindo as camadas de autenticação e verificação.

---

## Tecnologias e Metodologias
* **Análise de Vulnerabilidades:** Frameworks de segurança para IA (OWASP Top 10 for LLMs).
* **Monitoramento de Logs:** Identificação de padrões de comportamento anômalos em interações com o Agente.
* **Documentação Técnica:** Estruturação de relatórios de riscos e sugestões de mitigação (Guardrails).

---

## Principais Conclusões
1.  A automação sem camadas de "Human-in-the-loop" aumenta drasticamente o risco de execução de comandos não autorizados.
2.  A implementação de **Guardrails** robustos é essencial para filtrar inputs e sanitizar outputs antes que cheguem ao usuário final ou a sistemas críticos.

---

##  Autora
* **Tayná Soares** - [LinkedIn](https://www.linkedin.com/in/tayna-soares-4394ba150)
* Formação em Analista de Dados (EBAC) e Cibersegurança (Cisco).
