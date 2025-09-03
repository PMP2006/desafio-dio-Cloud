# desafio-dio-Cloud
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data:01/09/2025
Empresa: Abstergo Industries 
Responsável: Pedro Macedo Paula

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Pedro Macedo Paula. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.
<br><br>
## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **Ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco:** Armazenamento em nuvem escalável e de baixo custo.
- **Caso de uso:** A empresa utilizava servidores locais para armazenar grandes volumes de dados. Com a migração para o Amazon S3, os custos de manutenção e hardware foram eliminados, e passou-se a pagar apenas pelo uso efetivo de armazenamento. Além disso, políticas de lifecycle foram aplicadas, movendo arquivos menos acessados para classes de armazenamento mais baratas, como S3 Glacier, garantindo economia contínua.

Etapa 2: 
- **Ferramenta:** Amazon EC2 com instâncias Spot
- **Foco:** Redução de custos em processamento.
- **Caso de uso:** A empresa possuía workloads de processamento batch e testes que eram executados em servidores dedicados sem qualquer pausa. Com a adoção de EC2 com instâncias Spot, houve redução de até 70% nos custos de computação, mantendo a performance necessária para tarefas que não exigem alta disponibilidade contínua.

Etapa 3: 
- **Ferramenta:** AWS Lambda 
- **Foco:** Execução de código sob demanda (Serverless).
- **Caso de uso:** Diversos microprocessos rodavam em servidores dedicados, mesmo quando não estavam em uso. Com a implementação do AWS Lambda, a empresa passou a executar funções apenas quando necessário, sem a necessidade de manter infraestrutura ligada 24h. Isso reduziu custos diretos de servidores e energia, além de aumentar a escalabilidade.

<br><br>

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado: Redução imediata de custos, escalabilidade sob demanda, maior eficiência e produtividade, eliminação de gastos com infraestrutura física e manutenção. O que, no geral, aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- [Amazon S3](https://aws.amazon.com/pt/s3/)
- [Amazon S3 - Prós/Contras](https://cloudmounter.net/pros-and-cons-of-amazon-s3/)
- [Amazon EC2 Spot - Prós/Contras](https://www.finout.io/blog/aws-spot-instances)
- [Amazon EC2 Spot](https://aws.amazon.com/pt/ec2/spot/)
- [AWS Labmda](https://aws.amazon.com/pt/lambda/)
- [7 Benefícios AWS Labmda](https://www.checkpoint.com/pt/cyber-hub/cloud-security/what-is-serverless-security/benefits-of-aws-lambda-for-cloud-computing/)

Assinatura do Responsável pelo Projeto:

Pedro Macedo Paula

<br>

Orientado por [Felipe Aguiar](https://github.com/felipeAguiarCode) e [Willyan Guimarães](https://github.com/willyancaetano)
