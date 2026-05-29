# Veterinary CRM – Projeto Salesforce

## Visão Geral

Implementação de CRM Salesforce para uma clínica veterinária, com foco na gestão de clientes, pacientes (animais), agendamentos e histórico médico.

---

## Problema de Negócio

Clínicas veterinárias normalmente gerenciam dados de clientes e pacientes em planilhas e sistemas desconectados, gerando consultas perdidas, registros extraviados e falhas na comunicação com os tutores.

Este projeto resolve isso centralizando todas as informações e automatizando os principais processos dentro do Salesforce.

---

## Solução

- Objetos customizados para **Pacientes (Animais)** vinculados às contas dos tutores
- **Lembretes de consulta** automatizados via Salesforce Flow
- **Dashboard** com visão de consultas agendadas, pacientes ativos e receita por serviço
- Gestão de Cases para **histórico médico e tratamentos**

---

## Objetos e Customizações

| Objeto | Tipo | Descrição |
|---|---|---|
| Paciente | Objeto Customizado | Dados do animal (nome, espécie, raça, idade) |
| Agendamento | Objeto Customizado | Controle de consultas marcadas |
| Account | Padrão (modificado) | Representa os tutores |
| Case | Padrão (modificado) | Histórico médico e tratamentos |

---

## Automação (Salesforce Flow)

- **Flow de Lembrete de Consulta** – Envia notificação 24h antes da consulta agendada
- **Flow de Boas-vindas a Novo Paciente** – Atribui responsável e cria tarefa de acompanhamento no cadastro

---

## Reports & Dashboards

- Consultas por mês
- Pacientes por espécie
- Receita por tipo de serviço
- Cases abertos por veterinário

---

## Screenshots

> *(Adicione imagens na pasta `/images` e referencie aqui)*

---

## Aprendizados

- Criação de objetos customizados e relacionamentos
- Flow Builder para automação de processos
- Design de Dashboards para visibilidade operacional
