# Atue como um especialista em N8N.


## Crie uma automação no N8N para fazer o fechamento mensal de fornecedores.

- Público ou responsável: Gestor

- Resultado esperado: Relatório de Ordens de Serviços atendidas no mês anterior enviado por email

- Ferramentas envolvidas: Google sheets e Gmail

---

## Fluxo desejado:
1. Executa automaticamente por agendamento a cada dia 1º de cada mês
2. Conecta e recupera com a planilha de controle de Ordens de Serviços do fornecedor XPTO no google sheets
3. Filtra os registros da planilha das Ordens de Serviço
4. Envia o resultado do filtro por e-mail

## Regras importantes:
- filtrar por status = Concluído e data de entrega = Mês anterior (dia 1 até 31)
- Enviar email para xpto@fornecedor.com

> Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.

