# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 11 de maio de 2026
**Empresa:** Abstergo Industries
**Responsável:** Arthur Fernandes

## Introdução

Este relatório detalha o processo de implementação de ferramentas na Abstergo Industries, com o objetivo primordial de otimizar a infraestrutura de TI através da adoção estratégica de serviços da Amazon Web Services (AWS). A iniciativa visa a redução imediata de custos operacionais e a elevação da eficiência, alinhando a empresa às melhores práticas de gestão de recursos em nuvem.

## Descrição do Projeto

O projeto de implementação foi estruturado em três etapas distintas, cada uma focada na integração de um serviço AWS específico, selecionado por seu potencial de impacto direto na diminuição de despesas e na melhoria da performance. A seguir, são detalhadaas as ferramentas e seus respectivos casos de uso:

### Etapa 1: Amazon S3 (Simple Storage Service)

- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)

- **Foco da ferramenta:** Armazenamento de objetos escalável, durável e de baixo custo, com diversas classes de armazenamento e políticas de ciclo de vida para otimização de custos.

- **Descrição de caso de uso:** A primeira fase do projeto consistiu na migração de volumes significativos de dados legados e rotinas de backup de servidores *on-premise* para o Amazon S3. Esta ação permite a desativação de infraestrutura de armazenamento local, eliminando custos de manutenção e *hardware*. Adicionalmente, foram implementadas políticas de ciclo de vida que automaticamente movem dados acessados com pouca frequência para classes de armazenamento mais econômicas, como S3 Infrequent Access e S3 Glacier, garantindo uma gestão de custos contínua e eficiente.

### Etapa 2: AWS Lambda

- **Nome da ferramenta:** AWS Lambda

- **Foco da ferramenta:** Serviço de computação *serverless* que executa código em resposta a eventos, sem a necessidade de provisionar ou gerenciar servidores, com um modelo de precificação baseado no consumo real.

- **Descrição de caso de uso:** Na segunda etapa, scripts de automação existentes e tarefas agendadas, como processamento de dados em lote e geração de relatórios, foram refatorados e migrados para funções AWS Lambda. Esta transição para uma arquitetura *serverless* elimina a necessidade de manter servidores dedicados para essas tarefas, que frequentemente operavam com capacidade ociosa. O modelo de pagamento por execução do Lambda assegura que a Abstergo Industries pague apenas pelo tempo de computação efetivamente utilizado, resultando em uma redução drástica dos custos operacionais e maior agilidade no desenvolvimento.

### Etapa 3: Amazon EC2 Spot Instances

- **Nome da ferramenta:** Amazon EC2 Spot Instances

- **Foco da ferramenta:** Capacidade de computação EC2 não utilizada, oferecida a preços significativamente mais baixos em comparação com as instâncias On-Demand, ideal para cargas de trabalho flexíveis e tolerantes a interrupções.

- **Descrição de caso de uso:** A terceira e última etapa focou na otimização dos custos de computação para cargas de trabalho não críticas. Para tarefas como processamento de dados em larga escala, simulações, ambientes de desenvolvimento e teste, e renderização, foram adotadas as Amazon EC2 Spot Instances. Esta estratégia permite aproveitar a capacidade ociosa da AWS a um custo muito reduzido, complementando o uso de instâncias On-Demand para aplicações que exigem alta disponibilidade. A implementação de Spot Instances proporciona uma economia substancial nos custos de infraestrutura, sem comprometer a execução de processos que podem ser reiniciados ou distribuídos.

## Conclusão

A implementação estratégica dos serviços AWS – Amazon S3, AWS Lambda e Amazon EC2 Spot Instances – na Abstergo Industries representa um marco fundamental na modernização de nossa infraestrutura de TI. Espera-se que esta iniciativa proporcione uma **redução imediata e sustentável nos custos operacionais**, ao mesmo tempo em que **aumenta a agilidade, a escalabilidade e a resiliência** de nossos sistemas. A otimização do armazenamento, a eficiência da computação *serverless* e a economia com recursos de processamento flexíveis são benefícios diretos que impulsionarão a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização e a exploração de novas tecnologias em nuvem para consolidar a posição da Abstergo Industries como líder em inovação e eficiência tecnológica.

## Anexos

- Documentação técnica dos serviços AWS implementados

- Planilhas de comparação de custos (antes e depois da implementação)

- Relatórios de monitoramento de performance e utilização de recursos

- Manuais de boas práticas para gestão de custos em nuvem

**Assinatura do Responsável pelo Projeto:**

Arthur Fernandes

