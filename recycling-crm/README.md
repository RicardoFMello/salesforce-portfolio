# Recycling CRM – Projeto Salesforce

## Visão Geral

Implementação de CRM Salesforce para uma empresa de reciclagem, com foco na gestão de parceiros de coleta, agendamento de retiradas e acompanhamento de volume de materiais e impacto ambiental.

---

## Problema de Negócio

Operações de reciclagem envolvem múltiplos parceiros (empresas, condomínios, pontos públicos), agendamentos irregulares de coleta e necessidade de reportar métricas ambientais. Gerenciar isso manualmente gera falhas operacionais e perda de dados.

---

## Solução

- Gestão de parceiros com **segmentação customizada de Accounts**
- **Agendamento de coletas** automatizado via Salesforce Flow
- **Dashboard de impacto ambiental** com volume coletado por tipo de material
- Gestão de Cases para **problemas e reclamações de coleta**

---

## Objetos e Customizações

| Objeto | Tipo | Descrição |
|---|---|---|
| Account | Padrão (modificado) | Parceiros de coleta (empresas, condomínios, pontos públicos) |
| Coleta | Objeto Customizado | Retiradas agendadas com data, local e material |
| Material | Objeto Customizado | Tipo de reciclável (plástico, metal, papel, vidro) |
| Case | Padrão (modificado) | Problemas, reclamações e acompanhamentos |

---

## Automação (Salesforce Flow)

- **Flow de Agendamento de Coleta** – Cria automaticamente um registro de coleta quando o parceiro solicita retirada
- **Flow de Alerta de Coleta Atrasada** – Notifica a equipe responsável quando a coleta passa da data prevista sem ser realizada

---

## Reports & Dashboards

- Volume coletado por tipo de material (mensal)
- Parceiros ativos por região
- Coletas em atraso
- Resumo de impacto ambiental (kg desviados de aterro sanitário)

---

## Screenshots

> *(Adicione imagens na pasta `/images` e referencie aqui)*

---

## Aprendizados

- Relacionamentos entre objetos customizados e modelagem de dados
- Automação de Flow para operações
- Relatórios de impacto para métricas de sustentabilidade
