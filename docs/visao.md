# Escopo

### In Scope (Incluso)
- Cadastro de usuários (atendentes, médicos e pacientes)
- Disponibilidade de horários de cada médico
- Cadastro de pacientes
- Agendamento e cancelamento de consultas
- Exibição de erro em caso de conflito de horários (choque de agendas)

### Out of Scope (Fora)
- Envio de mensagens para médicos
- Prontuário eletrônico
- Faturamento e convênios
- Notificações em tempo real

---

## Regras de Negócio (RB)
- Consultas não podem se sobrepor no mesmo horário
- Consultas só podem ser agendadas dentro do horário de atendimento do médico
- Duração padrão de cada consulta: 30 minutos

---

## Premissas
- Horário comercial de funcionamento: das 08h às 18h
- Banco de dados inicial com capacidade para até 500 pacientes

---

## Stakeholders
- Atendentes
- Médicos
- Pacientes
- Gestor da clínica