# Luxury Cars CRM – Projeto Salesforce

## Visão Geral

Implementação de CRM Salesforce para uma concessionária de carros de luxo, com foco em gestão de Leads, acompanhamento do pipeline de vendas e Dashboards de performance.

---

## Problema de Negócio

Vendas de alto valor como veículos de luxo exigem rastreamento preciso de Leads, follow-up consistente e visibilidade sobre a saúde do pipeline. Sem um CRM estruturado, negócios são perdidos e o desempenho comercial se torna impossível de mensurar.

---

## Solução

- Pipeline de **Leads e Oportunidades** customizado para vendas de veículos de alto valor
- **Tarefas de follow-up** automatizadas quando Leads ficam sem atividade
- **Dashboards de performance** para gestores
- Visualizações customizadas de **Account e Contact** para clientes VIP

---

## Objetos e Customizações

| Objeto | Tipo | Descrição |
|---|---|---|
| Lead | Padrão (modificado) | Compradores potenciais com campo de interesse por modelo |
| Opportunity | Padrão (modificado) | Negociações ativas com modelo e valor do veículo |
| Account | Padrão (modificado) | Perfis de clientes VIP |
| Veículo | Objeto Customizado | Controle de estoque |

---

## Automação (Salesforce Flow)

- **Flow de Reengajamento de Lead Frio** – Cria tarefa para o vendedor quando o Lead fica 7 dias sem atividade
- **Flow de Notificação de Venda Fechada** – Alerta o gestor quando uma Opportunity é marcada como Closed Won

---

## Reports & Dashboards

- Pipeline por etapa e data prevista de fechamento
- Receita por vendedor
- Performance por origem de Lead
- Vendas mensais vs meta

---

## Screenshots

> *(Adicione imagens na pasta `/images` e referencie aqui)*

---

## Aprendizados

- Configuração de pipeline no Sales Cloud
- Processo de conversão de Lead para Opportunity
- Design de Dashboard executivo
