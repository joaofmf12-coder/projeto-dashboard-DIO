Este projeto consiste na criação de **dois dashboards interativos no Excel** para análise de dados
de assinaturas do **Xbox Game Pass**, simulando um cenário real de apresentação
de resultados para a diretoria de uma empresa de gaming/entretenimento digital.

O objetivo principal é transformar dados brutos de assinantes em insights visuais
e estratégicos, utilizando boas práticas de visualização de dados, paleta de cores
consistente com a identidade visual Xbox e fórmulas dinâmicas do Excel. A idéia final é mostrar 
apenas os dashboards.

## 📊 Dashboards

### Dashboard 1 — Versão Original (feito em aula)

O primeiro dashboard foi desenvolvido durante as aulas como exercício prático de
construção de painéis gerenciais no Excel. Ele aborda perguntas de negócio como:

- **Pergunta 1:** Qual o faturamento total de vendas de planos anuais?
- **Pergunta 2:** Qual o faturamento de planos anuais separado por auto renovação?
- **Pergunta 3:** Total de vendas de assinaturas do EA Play
- **Pergunta 4:** Total de vendas de assinaturas do Minecraft Season Pass

Utiliza tabelas dinâmicas (Pivot Tables) na aba `Cálculos` como base para os gráficos.

### Dashboard 2 — Criação complementar

O segundo dashboard (`Dashboard V2`) foi criado posteriormente, trazendo uma visão mais completa
dos dados. Foi Inclui:

**6 KPIs principais:**
| Indicador | Valor |
| --- | --- |
| Total de Assinantes | 295 |
| Faturamento Total | R$ 7.633 |
| Ticket Médio | R$ 25,87 |
| Desconto Total (Cupons) | R$ 2.122 |
| Taxa de Auto Renovação | 50,2% |
| Assinantes EA Play | 98 |

**6 Gráficos dinâmicos:**
1. 📊 Faturamento por Plano (barras horizontais)
2. 🍩 Distribuição por Tipo de Assinatura (rosca)
3. 🥧 Auto Renovação Sim vs Não (pizza)
4. 📊 Faturamento Plano × Tipo (colunas empilhadas)
5. 📈 Evolução Mensal de Faturamento (linha com marcadores)
6. 📊 Adesão aos Season Passes (barras empilhadas)



## 🗂️ Estrutura do Arquivo

```
📁 xbox-gamepass-dashboard.xlsx
│
├── 🎨 Assets          → Paleta de cores, logos e ícones de referência
├── 📋 Bases           → Base de dados com 295 assinantes (13 colunas)
├── 🔢 Cálculos        → Tabelas dinâmicas e perguntas de negócio (Dashboard 1)
├── 📊 Dashboard       → Dashboard original (feito em aula)
└── 📊 Dashboard V2    → Dashboard aprimorado (criado com IA)
```

## 📦 Dados Utilizados

A base de dados (`Bases`) contém **295 registros** de assinantes fictícios com as
seguintes colunas:

| # | Coluna | Descrição | Exemplo |
| --- | --- | --- | --- |
| 1 | `Subscriber ID` | Identificador único do assinante | 3231 |
| 2 | `Name` | Nome do assinante | João Silva |
| 3 | `Plan` | Plano contratado (Core, Standard, Ultimate) | Ultimate |
| 4 | `Start Date` | Data de início da assinatura | 01/01/2024 |
| 5 | `Auto Renewal` | Renovação automática (Yes/No) | Yes |
| 6 | `Subscription Price` | Preço do plano base | R$ 15,00 |
| 7 | `Subscription Type` | Tipo (Monthly, Quarterly, Annual) | Monthly |
| 8 | `EA Play Season Pass` | Possui EA Play (Yes/No) | Yes |
| 9 | `EA Play Season Pass Price` | Preço do EA Play | R$ 30,00 |
| 10 | `Minecraft Season Pass` | Possui Minecraft Pass (Yes/No) | Yes |
| 11 | `Minecraft Season Pass Price` | Preço do Minecraft Pass | R$ 20,00 |
| 12 | `Coupon Value` | Valor do cupom de desconto | R$ 5,00 |
| 13 | `Total Value` | Valor total cobrado | R$ 60,00 |

---

## 📄 Observação

Este projeto é de uso educacional. Os dados são fictícios e não representam
informações reais de assinantes do Xbox Game Pass.


