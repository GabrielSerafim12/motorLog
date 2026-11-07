# Plano inicial de testes manuais

| ID | Cenário | Resultado esperado |
|---|---|---|
| T01 | Escolher 0 no menu | Encerrar sem erro |
| T02 | Digitar texto na opção | Solicitar inteiro novamente |
| T03 | Cadastrar placa duplicada | Bloquear duplicidade |
| T04 | Cadastrar CPF duplicado | Bloquear duplicidade |
| T05 | Multa com motorista inexistente | Impedir registro |
| T06 | Multa com veículo inexistente | Impedir registro |
| T07 | Multa válida | Atualizar vetor e célula da matriz uma vez |
| T08 | Consultar placa/CPF inexistente | Informar não encontrado |
| T09 | Locar veículo indisponível | Impedir locação |
| T10 | CNH incompatível | Impedir locação |
| T11 | Listar tipos diferentes de veículo | Exibir dados específicos |
| T12 | Estatísticas sem registros | Não lançar exceção nem dividir por zero |