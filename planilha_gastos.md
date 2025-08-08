# Planilha de Projeção de Custos AWS

## Visão Geral  
Esta planilha serve para calcular uma estimativa dos custos dos serviços AWS que você pretende utilizar.

## Principais Itens que Impactam no Custo

1. **Amazon EC2**  
   - Tipo da instância escolhida  
   - Quantidade de horas em operação  
   - Gastos com armazenamento anexado (EBS)

2. **Amazon S3**  
   - Quantidade de dados armazenados (em GB)  
   - Número de requisições PUT, GET, LIST  
   - Volume de dados transferidos para fora da AWS

3. **AWS Lambda**  
   - Total de execuções mensais  
   - Tempo médio de execução por função

4. **Outros Serviços**  
   - Custos relacionados a RDS, CloudFront, SNS, entre outros.

## Exemplo de Estimativa

| Serviço        | Detalhes                  | Custo Aproximado   |
|----------------|---------------------------|--------------------|
| EC2            | Instância t3.small        | $0.0208 por hora   |
| S3             | 150 GB de armazenamento   | $3.45 mensal       |
| Lambda         | 1,5 milhão de execuções   | $0.30              |

## Considerações Finais  
Manter uma planilha atualizada para acompanhar os custos é essencial para controlar gastos e evitar surpresas na fatura da AWS, ajudando a planejar melhor o uso dos recursos.
