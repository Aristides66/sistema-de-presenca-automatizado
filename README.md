
# 🏫 Sistema de Presença Automatizada

## 📌 Sobre o projeto

O **Sistema de Presença Automatizada** é um projeto que busca facilitar o registro de presença dos alunos nas escolas por meio de um sistema de reconhecimento automatizado.

A solução tem como objetivo ajudar escolas e professores a controlar a presença dos estudantes e permitir que pais e responsáveis acompanhem a chegada dos alunos à escola.

## 🎯 Problema

O projeto busca resolver dois problemas principais:

- **Segurança dos alunos:** ajudar a confirmar a chegada dos estudantes à escola e fornecer informações aos responsáveis.
- **Organização escolar:** reduzir o trabalho manual dos professores e funcionários no registro de presença.

## 💡 Solução proposta

Desenvolver um sistema de reconhecimento de alunos capaz de registrar a presença de forma automatizada e facilitar a comunicação entre a escola e os responsáveis.

O sistema pretende:

- Automatizar o registro de presença.
- Facilitar o acompanhamento da chegada dos alunos.
- Melhorar a comunicação entre escola e responsáveis.
- Reduzir erros no registro manual.
- Identificar falhas e propor melhorias para aumentar a confiabilidade do sistema.

**Importante:** o reconhecimento automatizado deverá ser testado e acompanhado de um procedimento de verificação manual quando houver dúvidas ou falhas.

## 👥 Público-alvo

- Pais, mães e responsáveis pelos alunos.
- Escolas e instituições de ensino.
- Professores e funcionários responsáveis pela frequência escolar.

## 🏁 Objetivo da Sprint

A sprint tem como objetivo identificar possíveis falhas no projeto e propor melhorias para corrigi-las.

### Tarefas planejadas

- [ ] Entender como acontece a chegada dos alunos à escola.
- [ ] Identificar quantos pais e responsáveis têm acesso à tecnologia.
- [ ] Propor alternativas para responsáveis com dificuldades de acesso à tecnologia.
- [ ] Fazer orçamentos dos materiais e recursos necessários.
- [ ] Identificar possíveis falhas no reconhecimento dos alunos.
- [ ] Avaliar a comunicação das notificações aos responsáveis.
- [ ] Propor melhorias para aumentar a segurança e a confiabilidade do sistema.

## 📊 Painel de Métricas

Para acompanhar o desempenho do produto, a equipe utilizará métricas de produto e de código.

As métricas escolhidas são:

| Métrica | Tipo | Objetivo |
|---|---|---|
| Reconhecimento correto dos alunos | Produto | Avaliar a precisão do reconhecimento. |
| Entrega de notificações | Produto | Verificar se os responsáveis recebem as informações. |
| NPS | Produto | Medir a disposição dos usuários em recomendar o sistema. |
| Bugs abertos | Código | Acompanhar erros que precisam ser corrigidos. |
| Testes automatizados aprovados | Código | Avaliar a confiabilidade do código. |

Os cálculos de NPS, retenção, churn e o funil AARRR estão documentados no arquivo [`metricas/painel.md`](metricas/painel.md).

**Situação dos dados:** os valores iniciais do painel são simulados para fins acadêmicos e deverão ser substituídos por dados reais quando disponíveis.

## 📈 Decisão baseada em métricas

A decisão proposta é simplificar o cadastro e criar orientações para pais e responsáveis que tenham dificuldades com tecnologia.

O painel simulado identificou uma perda de **40% entre aquisição e ativação**, a maior queda entre as etapas aplicáveis do funil AARRR.

### Meta

Aumentar a taxa de ativação de 60% para pelo menos 75%.

### Responsáveis

- **Aristisdes:** responsável pelo produto.
- **José Henrique:** responsável pela comunicação.
- **Taislan:** responsável pela experiência.
- **Davyson:** responsável pela tecnologia e organização.

O registro da decisão está disponível em [`metricas/decisao.md`](metricas/decisao.md).

## 🛠️ Tecnologias e recursos

As tecnologias e os materiais necessários ainda deverão ser definidos conforme o desenvolvimento do projeto.

A equipe deverá avaliar:

- Recursos de reconhecimento de alunos.
- Equipamentos necessários para o funcionamento do sistema.
- Infraestrutura de software e hardware.
- Mecanismo de envio de notificações.
- Proteção e controle de acesso aos dados dos alunos.

## 🔒 Segurança e privacidade

Como o projeto envolve dados de alunos e possivelmente reconhecimento facial, será necessário:

- Proteger os dados pessoais dos estudantes.
- Restringir o acesso às informações aos usuários autorizados.
- Avaliar os requisitos da LGPD e as regras aplicáveis ao tratamento de dados de crianças e adolescentes.
- Evitar que um reconhecimento incerto confirme automaticamente a presença.
- Prever conferência manual em caso de falhas.
- Definir como os dados serão armazenados, protegidos e excluídos.

## 👨‍💻 Equipe

| Integrante | Responsabilidade |
|---|---|
| Aristisdes | Responsável pelo Produto |
| José Henrique | Responsável pela Comunicação |
| Taislan | Responsável pela Experiência |
| Davyson | Responsável pela Tecnologia e Organização |

## 📁 Estrutura do repositório

```text
Sistema-De-Presenca-Automatizada/
├── README.md
└── metricas/
    ├── painel.md
    └── decisao.md
```

## 🚀 Próximos passos

1. Entender o processo atual de entrada dos alunos.
2. Identificar as necessidades dos pais, responsáveis e funcionários.
3. Levantar os materiais e recursos necessários.
4. Testar a solução e identificar falhas.
5. Implementar melhorias e acompanhar os resultados pelas métricas.
6. Revisar os indicadores após as mudanças.

## 📌 Conclusão

O Sistema de Presença Automatizada busca tornar o registro de presença mais eficiente e melhorar a comunicação entre escolas e responsáveis.

A equipe pretende identificar falhas, propor melhorias e utilizar métricas para tomar decisões fundamentadas em dados, priorizando a confiabilidade do sistema, a experiência dos usuários e a segurança das informações dos alunos.

## Equipe
- Aristisdes - Responsavel Pelo Produto
- José Henrique - Responsavel pela a Comunicação
- Taislan - Responsavel pela Experiencia
- Davyson - Responsavel pela a tecnologia e organização
- João Victor - Responsalvel pelo marketing