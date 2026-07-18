# PMS-DOC-004 — Jornada Assistencial do Paciente

| Campo  | Valor                            |
| ------ | -------------------------------- |
| Código | PMS-DOC-004                      |
| Título | Jornada Assistencial do Paciente |
| Versão | 1.0.0                            |
| Status | Aprovado                         |
| Data   | 18/07/2026                       |

---

# 1. Objetivo

Este documento define a jornada assistencial do paciente dentro do Módulo Hospital do PMS.

Seu objetivo é descrever, em alto nível, as etapas percorridas pelo paciente desde sua chegada à unidade até o encerramento do atendimento, independentemente do tipo de entrada.

Este documento servirá como referência para o desenvolvimento dos módulos assistenciais e administrativos relacionados ao atendimento hospitalar.

---

# 2. Princípios

A jornada assistencial deve obedecer aos seguintes princípios:

* O paciente é o centro do processo.
* Cada atendimento possui rastreabilidade completa.
* As informações devem ser registradas uma única vez e reutilizadas sempre que possível.
* O prontuário do paciente é único e contínuo.
* O fluxo deve se adaptar à realidade operacional da unidade.

---

# 3. Formas de Entrada

O paciente poderá iniciar atendimento por diferentes formas:

* Demanda espontânea.
* Ambulância.
* Transporte sanitário.
* Encaminhamento de outra unidade.
* Retorno previamente orientado.
* Atendimento pediátrico.

Cada forma de entrada poderá possuir regras específicas sem alterar a estrutura principal da jornada.

---

# 4. Etapas da Jornada

## 4.1 Chegada

O paciente chega à unidade.

Nesta etapa ainda não existe atendimento ativo.

---

## 4.2 Recepção

A recepção deverá:

* localizar o paciente no cadastro local;
* consultar bases externas quando necessário e disponível;
* cadastrar novo paciente quando necessário;
* iniciar a jornada assistencial;
* identificar o setor de atendimento.

---

## 4.3 Triagem

Nesta etapa poderão ser registrados:

* sinais vitais;
* peso;
* altura;
* queixa principal;
* observações iniciais.

O protocolo de classificação de risco será configurável e poderá ser ativado conforme decisão da gestão da unidade.

---

## 4.4 Espera para Atendimento Médico

Após a triagem o paciente aguardará chamada para atendimento conforme a fila do setor.

O gerenciamento das filas será realizado pelo PMS.

---

## 4.5 Atendimento Médico

O profissional poderá:

* registrar evolução;
* solicitar exames;
* emitir prescrições;
* emitir receitas;
* emitir atestados;
* emitir declarações;
* solicitar internação;
* encaminhar para observação;
* conceder alta;
* solicitar transferência.

---

## 4.6 Exames

Quando solicitado:

* exame interno;
* exame externo.

Os resultados poderão ser:

* digitados diretamente no PMS;
* anexados em formato digital.

---

## 4.7 Medicação

Quando houver prescrição medicamentosa:

* a farmácia realizará a dispensação;
* a enfermagem registrará a administração da medicação;
* todas as etapas deverão possuir rastreabilidade.

---

## 4.8 Observação

O paciente poderá permanecer em observação.

Serão registrados:

* leito ou poltrona;
* evolução;
* sinais vitais;
* procedimentos;
* administração de medicamentos.

Ao término da observação o paciente poderá:

* receber alta;
* permanecer internado;
* retornar ao atendimento médico.

---

## 4.9 Internação

Quando indicada pelo médico:

* o paciente será vinculado a um leito;
* iniciará acompanhamento contínuo;
* poderão existir prescrições diárias;
* evoluções médicas;
* evoluções de enfermagem;
* dieta;
* exames;
* medicações.

---

## 4.10 Alta

A alta deverá ser registrada por profissional autorizado.

Poderão ser emitidos:

* resumo de alta;
* receita;
* orientações;
* atestado;
* declarações.

---

## 4.11 Transferência

Quando necessário o paciente poderá ser transferido para outra unidade.

O PMS deverá registrar toda a movimentação.

---

## 4.12 Óbito

Quando ocorrer, deverão existir registros específicos conforme legislação e normas vigentes.

As regras detalhadas serão definidas em documento próprio.

---

# 5. Fluxos Especiais

Além da jornada padrão, o PMS deverá suportar:

* paciente sem identificação;
* atendimento de emergência;
* paciente pediátrico;
* retorno;
* múltiplos acompanhantes;
* troca de acompanhante durante internação.

---

# 6. Encerramento da Jornada

A jornada somente será considerada encerrada quando todas as etapas obrigatórias do atendimento estiverem concluídas.

O prontuário permanecerá disponível para futuras consultas.

---

# 7. Considerações

A jornada descrita neste documento representa o fluxo lógico do paciente.

Os detalhes operacionais de cada etapa serão especificados nos documentos dos respectivos módulos.

---

# 8. Histórico de Alterações

| Versão | Data       | Descrição                                            |
| ------ | ---------- | ---------------------------------------------------- |
| 1.0.0  | 18/07/2026 | Criação inicial da jornada assistencial do paciente. |
