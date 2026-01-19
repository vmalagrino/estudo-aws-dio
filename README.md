# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: [data de ínicio do projeto]
Empresa: Abstergo Industries
Responsável: Victor Malagrino

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Victor Malagrino. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

- Nome: Amazon EC2 AutoScaling
- Foco da ferramenta: Ajustar de forma automática a capacidade computacional, reduzindo ou aumentando as instâncias de acordo com a demanda, evitando desperdícios desnecessários e garantindo alta disponibilidade.
- Descrição de caso de uso: Em períodos de pico de acesso à aplicação da Abstergo Industries, novas instâncias EC2 são criadas automaticamente. Em períodos de baixa, elas são encerradas para reduzir custos.

Etapa 2:

- Nome: Elastic Load Balancing - ELB
- Foco da ferramenta: Atuar como firewall em nível de instância, controlando o tráfego de entrada e saída por meio de regras que definem quais protocolos, portas e endereços IP podem acessar os recursos da AWS.
- Descrição de caso de uso: Os Security Groups serão utilizados para restringir o acesso às instâncias EC2, permitindo conexões apenas nas portas necessárias (como HTTP e HTTPS) e limitando acessos administrativos a endereços IP específicos, aumentando a segurança da infraestrutura e reduzindo riscos de acessos não autorizados. Por padrão opera em modo Statefull, permitindo todo o tráfego de saída e negando todo o tráfego de entrada.

Etapa 3:

- Nome: Network ACLs
- Foco da ferramenta: Valida a entrada e a saída do dados, gerando uma camada extra de proteção, funciona por comportamento Stateless (não é por que aquele dado entrou que ele vai sair).  
- Descrição de caso de uso: Verificar os dados que estão entrando e se eles tem a permissão para entrar, na saída ocorre o mesmo processo sendo a entra e a saída a mesma porta. 

## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado [benefícios das ferramentas]*, o que aumentarÃ¡ a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[lista de anexos, como manuais, documentos, planilhas, entre outros]

Responsável pelo Projeto:

Victor Malagrino
