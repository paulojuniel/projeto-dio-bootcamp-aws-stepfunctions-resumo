# projeto-dio-bootcamp-aws-stepfunctions-resumo
Resumo aws step functions para entrega no bootcamp da Dio



# AWS Step Functions: Resumo
 
 AWS Step Functions é um serviço gerenciado da AWS que facilita a coordenação de fluxos de trabalho complexos, permitindo a criação e o gerenciamento de sequências de tarefas, além de integrá-las com outros serviços da AWS de forma escalável e organizada. AWS Step Functions oferece um serviço low-code para gerenciar e criar fluxos de trabalho automatizados.

1. O que é o AWS Step Functions?
AWS Step Functions é um serviço que orquestra workflows de aplicações, coordenando múltiplas funções e serviços da AWS.
Ele ajuda a dividir tarefas complexas em etapas menores, chamadas de states (estados), que são organizadas e executadas de acordo com uma lógica definida.

3. Principais Componentes
States (Estados): Representam cada etapa do fluxo de trabalho, como tarefas, condições, esperas e escolhas.
State Machine (Máquina de Estado): Define o fluxo de um processo, com os estados e transições.
Transitions (Transições): Regras que determinam a sequência e condições para mover de um estado a outro.
Tasks (Tarefas): Ações específicas que são executadas, podendo chamar uma função Lambda, uma consulta no DynamoDB, ou outros serviços.

4. Tipos de Máquinas de Estado
Standard Workflows: Projetadas para fluxos complexos e de longa duração, suportando maior tolerância a falhas e reprocessamento.
Express Workflows: Mais rápidas e econômicas, ideais para cargas intensivas e com curta duração, mas com menos capacidade de recuperação e persistência.

5. Vantagens e Benefícios
Automação e Organização: Facilita a automação de processos complexos ao dividir tarefas e gerenciar a sequência de execução.
Escalabilidade: Gerenciado pela AWS, permite criar workflows escaláveis sem se preocupar com a infraestrutura.
Resiliência e Recuperação de Erros: Oferece mecanismos automáticos para lidar com falhas, reprocessando tarefas falhadas e mantendo logs detalhados.

6. Casos de Uso Comuns
Processamento de Dados: Fluxos ETL, como extração, transformação e carregamento de dados.
Processos de Negócio: Automatização de fluxos como aprovação de pedidos, onboarding de clientes, etc.
Orquestração de Microserviços: Coordenação e integração de múltiplos microserviços em um único fluxo de trabalho.

7. Integração com Outros Serviços AWS
AWS Step Functions se integra facilmente com vários serviços AWS, como AWS Lambda, DynamoDB, S3, SNS, SQS e API Gateway.
Essa integração simplifica a criação de aplicações sem servidor (serverless), distribuídas e escaláveis.

8. Modelo de Pagamento
O pagamento é feito com base na quantidade de transições de estado utilizadas dentro do fluxo de trabalho.
Esse modelo é vantajoso, pois permite controle de custos ao pagar apenas pelo que é efetivamente utilizado.

9. Ferramentas de Monitoramento e Depuração
AWS Step Functions oferece logs detalhados e métricas através do Amazon CloudWatch, permitindo monitorar cada etapa dos workflows.
Além disso, fornece gráficos de fluxo para visualizar o progresso e eventuais falhas nas execuções.

AWS Step Functions facilita a coordenação de processos complexos, melhora a automação e a resiliência de aplicações, além de oferecer um sistema de pagamento flexível e integração direta com diversos serviços AWS, sendo uma escolha eficiente para fluxos de trabalho modernos na nuvem.

## Referência

https://aws.amazon.com/pt/step-functions/
