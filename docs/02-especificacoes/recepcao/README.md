# PMS-ESP-001 — Módulo Recepção

| Campo | Valor |
|-------|--------|
| Código | PMS-ESP-001 |
| Módulo | Recepção |
| Versão | 1.0.0 |
| Status | Em elaboração |

---

# 1. Objetivo

O módulo Recepção é responsável pelo primeiro contato do paciente com a unidade de saúde.

Seu objetivo é identificar ou cadastrar o paciente, iniciar sua jornada assistencial, encaminhá-lo ao setor correto e manter o controle da fila de atendimento.

Este módulo deverá reduzir o tempo de atendimento da recepção, eliminar retrabalho e evitar cadastros duplicados.

---

# 2. Responsabilidades

O módulo deverá permitir:

- localizar pacientes já cadastrados;
- cadastrar novos pacientes;
- atualizar dados cadastrais;
- registrar acompanhantes;
- iniciar atendimento;
- encaminhar para triagem;
- encaminhar diretamente ao consultório quando necessário;
- emitir identificação do paciente;
- controlar filas;
- consultar histórico resumido;
- registrar forma de chegada.

---

# 3. Usuários

Podem utilizar este módulo:

- Recepcionista
- Supervisor da Recepção
- Coordenador
- Diretor (consulta)

---

# 4. Integrações previstas

- PEC e-SUS (consulta de pacientes)
- CADSUS (quando tecnicamente disponível)
- CNES
- Painel de chamadas
- Prontuário Eletrônico
- Módulo de Internação
- Transporte Sanitário

---

# 5. Fluxo Principal

Chegada

↓

Localizar paciente

↓

Paciente encontrado?

SIM

↓

Atualizar dados se necessário

↓

Abrir atendimento

↓

Encaminhar

↓

Fila

↓

Triagem

OU

Consultório

OU

Emergência

---

NÃO

↓

Cadastrar paciente

↓

Abrir atendimento

↓

Encaminhar
