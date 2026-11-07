# Arquitetura MotorLog

## Classes
- `Veiculo`: superclasse abstrata com dados comuns.
- `Automovel`, `Caminhao`, `Motocicleta`: subclasses de `Veiculo`.
- `Motorista`: dados pessoais e habilitação.
- `Multa`: infração, pontuação e índices do motorista/veículo.
- `MotorLog`: menu, fluxo, vetores, matriz e integração.

## Estruturas
- `Veiculo[50]` para a frota.
- `Motorista[50]` para os condutores.
- `Multa[200]` para as infrações.
- `int[50][50]` para matriz: linha = motorista; coluna = veículo.

## Dependências
Cadastro de multa depende de motorista e veículo existentes. Consultas dependem das buscas por CPF/placa. A matriz é atualizada no registro da multa. Locação depende da disponibilidade do veículo e da categoria da CNH.

## Restrição da entrega
O relatório técnico registra RNF01 como arquivo único `MotorLog.java`. As classes estão separadas aqui para facilitar desenvolvimento paralelo. Consolidar e testar em arquivo único antes da entrega, se a regra continuar obrigatória.
