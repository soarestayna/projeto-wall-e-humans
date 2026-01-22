# Relatório de Insights Estratégicos

**Projeto:** Investigação WALL-E: O Dilema do Agente Confiável  
**Autora:** Tayná Soares  
**Data:** Janeiro/2026

## 1. O Paradoxo da Automação e Hiper-Conveniência
A investigação revelou que a busca por uma "vida sem fricção" (Hiper-conveniência) é o maior vetor de risco para usuários de Agentes de IA. 
Ao delegar autonomia financeira e de dados, o usuário expande sua **Superfície de Ataque**. O sequestro de intenção via injeção de prompt não é 
apenas um erro técnico, é uma falha de design na confiança depositada na automação plena.

## 2. Padrões de Ataque Identificados (EDA)
Através da Análise Exploratória de Dados no dataset MPDD, foi identificado que ataques de injeção de prompt possuem um vocabulário estatisticamente previsível. 
* **Gatilhos Comuns:** Termos como `ignore`, `system`, `access`, `admin` e o padrão `DAN`.
* **Conclusão:** A previsibilidade desses termos justifica a implementação de um **Vigia de Machine Learning** capaz de realizar a triagem semântica antes do processamento do agente principal (O Analista Humano).

## 3. Conformidade e Transparência (LGPD)
O projeto identificou um "ponto cego" de privacidade na saída de dados (*egress traffic*).
* **Risco:** Falta de clareza sobre o destino final dos tokens de pagamento e identidades digitais.
* **Solução de Dados:** O monitoramento contínuo garante que o Agente opere apenas dentro de "Zonas Confiáveis", alinhando a conveniência
  tecnológica aos princípios de Finalidade e Transparência da LGPD.

## 4. Proposta: O Modelo de Defesa Híbrido (HITL)
A solução final recomendada não é a proibição da tecnologia, mas a **Triagem Assistida com Veredito Humano**:
1. **Escala:** O "Vigia" processa 100% dos dados e descarta o ruído seguro.
2. **Inteligência:** Casos suspeitos recebem *tags* de CTI para enriquecimento de contexto.
3. **Soberania:** A decisão final sobre transações críticas permanece com o **Analista Humano**, eliminando o risco de "passividade" total.

---
[🏠 Voltar para o README Principal](../README.md)
