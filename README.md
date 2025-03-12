# onboarding-amigotech-node-team-full

## Estudos

1. **Orçamento**
   - [x] Ajuste de saldo
   - [x] Aprovado sem financeiro
   - [x] Com financeiro
     - [x] Cartão + Cheque + Boleto + Crédito em conta
     - [x] Nota promissória

2. **Regra de banco de dados da criação de atendimento**
   - [x] Particular
     - [x] Cartão + Cheque + Boleto + Crédito em conta
     - [x] Crédito de Procedimento
     - [x] Crédito Pré-pago
     - [x] Dinheiro
     - [x] Nota promissória
   - [ ] Convênio
     - [x] SADT
     - [ ] SADT PF
     - [x] GHI
     - [ ] GHI PF
     - [ ] GHI INTERNAÇÃO
     - [x] CONSULTA
     - [x] CONSULTA PF
     - [ ] APAC
     - [ ] BPA
   - [x] Convênio + Repetir procedimento
   - [x] Convênio Executantes dos procedimentos (verificar como salva)
   - [x] EXAMES
   - [x] Cirurgia
   - [x] Bloqueio de agenda
   - [x] Itens importantes (verificar como salva no banco):
     - [x] Tipo de atendimento (T.A)
     - [x] Solicitante (Interno e Externo)

3. **Exercício**
   - [ ] Replicar a listagem da Agenda (atendimentos + bloqueios)

4. **Fluxo de sessões**
   - [ ] Particular
   - [ ] Convênio

5. **Exercício**
   - [ ] Implementar/ajustar o exercício 3 para contemplar sessões

6. **Fluxo de Paciente compartilhado**
   - [ ] Como funciona no banco de dados essa regra e como se aplica no sistema

7. **Exercício**
   - [ ] Implementar a regra de paciente compartilhado para trocar o nome do paciente para "Paciente apagado" quando o compartilhamento deixar de existir

8. **Fluxo contas a Receber (particular)**
   - [ ] Lote de cartão antigo
   - [ ] Lote de cartão novo
   - [x] Dinheiro
   - [x] Cheque + Boleto + Crédito em conta
   - [ ] Nota Promissória (*** IMPORTANTE ***)

9. **Fluxo desfazer baixa (particular)**
   - [ ] Lote de cartão antigo
   - [ ] Lote de cartão novo
   - [ ] Dinheiro
   - [ ] Cheque + Boleto + Crédito em conta
   - [ ] Nota Promissória (*** IMPORTANTE ***)

10. **Fluxo Convênio**
    - [ ] Guias pendentes
    - [ ] Lotes pendentes
    - [ ] Lotes enviados
    - [ ] Lotes recebidos
    - [ ] Extrato
    - [ ] Baixa de lote total
    - [ ] Baixa de lote parcial
    - [ ] Glosa
    - [ ] Glosas pendentes
    - [ ] Glosas recursadas

11. **Desfazer baixa de lotes**

12. **Contas a pagar (Recorrência)**
    - [ ] Recorrência indeterminada
    - [ ] Recorrência determinada
    - [ ] Parcelamento
    - [ ] Cronjob
