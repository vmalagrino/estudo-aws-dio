# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 19/01/2026
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

- Nome: Security Groups
- Foco da ferramenta: Atuar como firewall em nível de instância, controlando o tráfego de entrada e saída por meio de regras que definem quais protocolos, portas e endereços IP podem acessar os recursos da AWS.
- Descrição de caso de uso: Os Security Groups serão utilizados para restringir o acesso às instâncias EC2, permitindo conexões apenas nas portas necessárias (como HTTP e HTTPS) e limitando acessos administrativos a endereços IP específicos, aumentando a segurança da infraestrutura e reduzindo riscos de acessos não autorizados. Por padrão, os Security Groups operam de forma stateful e permitem todo o tráfego de saída, enquanto o tráfego de entrada só é autorizado quando explicitamente configurado.

Etapa 3:

- Nome: Amazon S3 Intelligent-Tiering
- Foco da ferramenta: O foco do S3 Intelligent-Tiering é otimização automática de custos, movendo objetos entre camadas de armazenamento com base no padrão de acesso, sem impacto na performance e sem necessidade de intervenção manual.
- Descrição de caso de uso: O Amazon S3 Intelligent-Tiering será utilizado para armazenar dados corporativos, como documentos, relatórios, backups e arquivos históricos, cujo padrão de acesso é imprevisível ou varia ao longo do tempo. O serviço monitora automaticamente os acessos aos objetos e os move entre camadas de armazenamento mais econômicas, garantindo redução de custos sem comprometer a disponibilidade ou a performance, eliminando a necessidade de gerenciamento manual do ciclo de vida dos dados.

## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado redução de custos desnecessários, ajustes de computação para melhor experiência do usuário, melhor performance de armazenamento e aumento de segurança nas instâncias, aumentando assim a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Responsável pelo Projeto:

Victor Malagrino
