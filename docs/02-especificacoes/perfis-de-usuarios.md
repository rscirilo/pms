# PMS-DOC-003 — Atores e Perfis de Usuários

| Campo  | Valor                       |
| ------ | --------------------------- |
| Código | PMS-DOC-003                 |
| Título | Atores e Perfis de Usuários |
| Versão | 1.0.0                       |
| Status | Aprovado                    |
| Data   | 18/07/2026                  |

---

# 1. Objetivo

Este documento identifica todos os atores que interagem com a Plataforma Municipal de Saúde (PMS), definindo seus papéis, responsabilidades e escopo de atuação.

Este documento **não define permissões detalhadas**. As regras de acesso serão especificadas em documento próprio durante a fase de arquitetura de segurança.

---

# 2. Conceitos

## Ator

Qualquer pessoa, setor ou sistema externo que interage com o PMS.

## Perfil

Conjunto de responsabilidades exercidas por um ator dentro da plataforma.

## Usuário

Pessoa autenticada no sistema, vinculada a um ou mais perfis.

---

# 3. Classificação dos Atores

Os atores do PMS são classificados em:

* Assistenciais
* Administrativos
* Apoio
* Gestão
* Externos
* Sistemas Integrados

---

# 4. Atores Assistenciais

## Recepcionista

Responsável pelo primeiro contato do paciente com a unidade.

Principais atividades:

* localizar paciente;
* cadastrar paciente;
* atualizar dados cadastrais;
* iniciar atendimento;
* emitir identificação do paciente;
* acompanhar o status do atendimento.

---

## Enfermeiro

Responsável pelas atividades assistenciais de enfermagem.

Principais atividades:

* triagem;
* classificação de risco (quando utilizada);
* evolução de enfermagem;
* administração de medicamentos;
* procedimentos;
* acompanhamento da observação;
* acompanhamento da internação.

---

## Técnico de Enfermagem

Responsável por atividades delegadas pela enfermagem.

Principais atividades:

* triagem;
* sinais vitais;
* administração de medicamentos;
* procedimentos;
* registros assistenciais.

---

## Médico

Responsável pela condução clínica do atendimento.

Principais atividades:

* consulta;
* diagnóstico;
* prescrições;
* solicitação de exames;
* atestados;
* declarações;
* evolução médica;
* alta médica;
* internação.

Especialidades poderão possuir fluxos específicos, mantendo a mesma estrutura básica.

---

## Pediatra

Especialização do perfil Médico, com atuação no fluxo pediátrico.

---

## Farmacêutico

Responsável pela gestão da farmácia.

Atividades previstas:

* dispensação;
* controle de estoque;
* rastreabilidade;
* conferência;
* inventário.

---

## Nutricionista

Responsável pela nutrição clínica e pela produção de dietas hospitalares.

---

## Laboratório

Responsável pelo processamento e registro de exames laboratoriais.

---

# 5. Atores Administrativos

## Almoxarife

Responsável pelo controle dos materiais de consumo e permanentes.

---

## RH

Responsável por:

* colaboradores;
* vínculos;
* escalas;
* plantões;
* férias;
* afastamentos.

---

## Faturamento

Responsável pela produção assistencial e faturamento.

Entre suas atribuições estão:

* BPA;
* conferência;
* produção;
* exportações.

---

## Administração

Responsável pela gestão administrativa da unidade.

---

# 6. Gestão

## Coordenadores

Gerenciam setores específicos.

Possuem acesso gerencial apenas às áreas sob sua responsabilidade.

---

## Diretor

Possui visão global da unidade e acesso aos indicadores gerenciais.

---

## Secretaria Municipal de Saúde

Possui acesso institucional às unidades sob sua gestão.

As permissões serão configuráveis conforme o perfil funcional.

---

# 7. Apoio

## Motorista

Atuação no módulo Transporte Sanitário.

---

## Higienização

Utilizará o módulo de chamados e ordens de serviço.

---

# 8. Usuários Externos

## Paciente

Em versões futuras poderá acessar:

* resultados;
* documentos;
* histórico;
* agendamentos.

---

## Acompanhante

Pessoa vinculada temporariamente ao paciente durante o atendimento ou internação.

Poderá receber declarações e possuir registro de contato.

---

# 9. Sistemas Externos

Entre os sistemas que poderão integrar-se ao PMS estão:

* PEC e-SUS
* CADSUS (quando tecnicamente viável)
* CNES
* BPA
* Outros sistemas oficiais que disponibilizem integração.

---

# 10. Considerações

Um mesmo usuário poderá possuir múltiplos perfis.

Exemplo:

* Médico e Coordenador;
* Enfermeiro e Diretor Técnico;
* Farmacêutico e Almoxarife.

O sistema deverá determinar automaticamente quais funcionalidades estarão disponíveis conforme os vínculos ativos do usuário.

---

# 11. Histórico de Alterações

| Versão | Data       | Descrição             |
| ------ | ---------- | --------------------- |
| 1.0.0  | 18/07/2026 | Criação do documento. |
