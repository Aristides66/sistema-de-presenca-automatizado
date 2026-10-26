
# Painel de Métricas — Sistema de Presença Automatizada

## 1. Informações do projeto

- **Produto:** Sistema de Presença Automatizada
- **Objetivo:** Automatizar o registro de presença dos alunos e facilitar a comunicação entre escola e responsáveis.
- **Público-alvo:** Pais, mães, responsáveis, escolas e professores.
- **Período analisado:** Outubro de 2026.
- **Situação dos dados:** Simulados para fins acadêmicos.

## 2. Métricas escolhidas

| Métrica | Tipo | Valor atual | Período | Se piorar, vamos... |
|---|---|---|---|---|
| Reconhecimento correto dos alunos | Produto | 90% | Outubro/2026 | Testar o reconhecimento e corrigir falhas. |
| Entrega de notificações aos responsáveis | Produto | 80% | Outubro/2026 | Investigar falhas no envio das notificações. |
| NPS | Produto | -10 | Outubro/2026 | Entrevistar usuários insatisfeitos. |
| Bugs abertos | Código | 8 bugs | Outubro/2026 | Priorizar a correção dos erros críticos. |
| Testes automatizados aprovados | Código | 85% | Outubro/2026 | Identificar os testes que falharam e corrigir os problemas. |

## 3. Cálculo do NPS

Pergunta: "De 0 a 10, quanto você recomendaria o Sistema de Presença Automatizada?"

**Respostas simuladas:** 10, 9, 9, 8, 8, 7, 6, 5, 4, 2.

- **Promotores (9–10):** 3 pessoas.
- **Neutros (7–8):** 3 pessoas.
- **Detratores (0–6):** 4 pessoas.

### Percentual de promotores

(3 / 10) x 100 = 30%

### Percentual de detratores

(4 / 10) x 100 = 40%

### Resultado do NPS

NPS = % de promotores - % de detratores

NPS = 30 - 40 = **-10**

**Interpretação:** O NPS negativo indica que existem mais detratores do que promotores. A equipe deve investigar problemas de confiança, facilidade de uso e funcionamento do sistema.

**Observação:** Para a entrega definitiva, substituir as notas simuladas por pelo menos 10 respostas reais.

## 4. Cálculo da retenção

Dados simulados:

- Usuários que começaram: 120.
- Usuários que voltaram: 90.

**Fórmula:**

Retenção = (usuários que voltaram / usuários que começaram) x 100

Retenção = (90 / 120) x 100

**Retenção = 75%**

**Interpretação:** 75% dos usuários retornaram ao sistema no período analisado.

## 5. Cálculo do churn

Dados simulados:

- Usuários no início: 120.
- Usuários que não retornaram: 30.

**Fórmula:**

Churn = (usuários que saíram / usuários no início) x 100

Churn = (30 / 120) x 100

**Churn = 25%**

### Conferência

Retenção + Churn = 100%

75% + 25% = **100%**

**Interpretação:** 25% dos usuários não retornaram no período analisado.

## 6. Funil AARRR

Os números abaixo são simulados.

| Etapa | Quantidade | Conversão em relação à etapa anterior |
|---|---:|---:|
| Aquisição | 200 pessoas | — |
| Ativação | 120 pessoas | 60% |
| Retenção | 90 pessoas | 75% |
| Receita | Não aplicável | Sistema gratuito |
| Recomendação | NPS -10 | Indicador de recomendação |

### Cálculo da conversão: Aquisição → Ativação

(120 / 200) x 100 = 60%

Perda = ((200 - 120) / 200) x 100

**Perda = 40%**

### Cálculo da conversão: Ativação → Retenção

(90 / 120) x 100 = 75%

Perda = ((120 - 90) / 120) x 100

**Perda = 25%**

### Maior queda do funil

A maior queda acontece entre **Aquisição e Ativação**, com perda de **40%**.

**Interpretação:** Das 200 pessoas que chegaram ao sistema, apenas 120 começaram a utilizá-lo. Isso pode indicar dificuldades no cadastro, falta de acesso à tecnologia ou falta de orientação aos responsáveis.

Como o sistema é considerado gratuito, a etapa Receita não será utilizada para identificar a maior queda. Caso o modelo de financiamento mude, a equipe poderá definir uma métrica financeira apropriada.

## 7. Decisão proposta

**Ação:** Simplificar o cadastro e criar orientações para pais, mães e responsáveis com dificuldades de acesso ou uso da tecnologia.

**Motivo:** A maior queda do funil é de 40% entre aquisição e ativação.

**Responsável:** Davyson — Tecnologia e Organização.

**Apoio:**
- Aristisdes — Responsável pelo Produto.
- José Henrique — Responsável pela Comunicação.
- Taislan — Responsável pela Experiência.

**Meta:** Aumentar a taxa de ativação de 60% para pelo menos 75%.

**Revisão:** 02/11/2026.

## 8. Conclusão

Os dados simulados indicam que a principal oportunidade de melhoria está no primeiro acesso ao Sistema de Presença Automatizada.

A equipe deverá simplificar o cadastro, orientar os responsáveis e verificar se essas mudanças aumentam a ativação. Também será importante corrigir bugs, testar o reconhecimento dos alunos e garantir que as notificações sejam entregues corretamente.