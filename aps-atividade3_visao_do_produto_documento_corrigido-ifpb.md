<h1>Visão do Produto</h1>

<h2>Sistema de Inventário de Equipamentos de Informática (SIEI)</h2>

<small>Versão 1.5</small>

---

## Histórico de revisões

|    Data    | Versão |           Descrição           |      Autor       |
| :--------: | :----: | :---------------------------: | :--------------: |
| 13/08/2024 |  1.0   |     Criação do documento      | Felipe Cartaxo, Sheila Lee |
| 19/08/2024 |  1.1   | Adicionadas novas informações | Caio Bernadelli, Felipe Cartaxo, Gabriel Oliveira, Michel Lavanere, Sheila Lee |
| 21/08/2024 |  1.2   | Realizada revisão de conteúdo | Caio Bernadelli, Felipe Cartaxo, Gabriel Oliveira, Michel Lavanere, Sheila Lee |
| 29/08/2024 |  1.3   | Adicionadas novas informações em "Descrição dos stakeholders e dos usuários" | Felipe Cartaxo |
| 29/08/2024 |  1.4   | Correção de redundâncias na seção "Funcionalidades" e "Benefícios" | Felipe Cartaxo, Sheila Lee |
| 29/08/2024 |   1.5  | Correção de inconsistências na seção "Características e funcionalidades de alto nível" e "Restrições" | Felipe Cartaxo, Sheila Lee |

---

## Sumário

- [Introdução](#introdução)
  - [Propósito](#propósito)
  - [Definições e abreviações](#definições-e-abreviações)
    - [Abreviações](#abreviações)
    - [Definições](#definições)
  - [Escopo do produto](#escopo-do-produto)
- [Posicionamento](#posicionamento)
  - [Oportunidade de negócios](#oportunidade-de-negócios)
  - [Descrição dos benefícios para os clientes e dos problemas resolvidos](#descrição-dos-benefícios-para-os-clientes-e-dos-problemas-resolvidos)
- [Descrição dos stakeholders e dos usuários](#descrição-dos-stakeholders-e-dos-usuários)
  - [Stakeholders](#stakeholders)
  - [Usuários e atores](#usuários-e-atores)
- [Descrição do ambiente de uso](#descrição-do-ambiente-de-uso)
  - [Ambiente de uso](#ambiente-de-uso)
  - [Necessidades principais quanto ao ambiente](#necessidades-principais-quanto-ao-ambiente)
- [Visão geral do produto](#visão-geral-do-produto)
  - [Visão geral](#visão-geral)
  - [Custo e venda](#custo-e-venda)
  - [Licenciamento e instalação](#licenciamento-e-instalação)
  - [Características e funcionalidades de alto nível](#características-e-funcionalidades-de-alto-nível)
  - [Restrições](#restrições)

# Introdução

O Documento de Visão do Produto (DVP) é um documento que descreve o produto de software que será desenvolvido. Ele descreve o problema que será resolvido, as principais necessidades dos stakeholders, as principais funcionalidades do sistema, as restrições do projeto, etc.

## Propósito

O objetivo deste documento é coletar, analisar e definir características e as necessidades de alto nível do **Sistema de Inventário de Equipamentos de Informática (SIEI).**

Ele se concentra nos recursos necessários aos stakeholders e aos usuários, e nas razões que levam a essas necessidades.

Os detalhes de como o **Sistema de Inventário de Equipamentos de Informática (SIEI)** atinge essas necessidades são descritos nas _especificações de casos de uso_ e nos _requisitos funcionais_.

## Definições e abreviações

### Abreviações

| Termo | Definição                                    |
| :---: | -------------------------------------------- |
| SIEI | Sistema de Inventário de Equipamentos de Informática |
| Empreender PB | Secretaria de Empreendedorismo da Paraíba |
| SGTI | Subgerência de Tecnologia da Informação |
| GLPI | Sistema de gerenciamento de chamados usado internamente na secretaria |
| OS | Ordem de Serviço |
|  UML  | Linguagem de Modelagem Unificada             |

### Definições

|    Termo    | Definição                                                                                                                       |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------- |
|   Usuário   | É um funcionário/estagiário da Subgerência de TI.                                                   |
| Gestor  | Servidor responsável pela SGTI.                                                               |
|   Equipamento de informática | Qualquer item de informática que possua patrimônio (desktop, notebook, monitor, impressora, switch etc).                                                             |
| Equipamento de consumo  | Qualquer item de informática que não possua patrimônio (cabos de rede, conectores RJ45, filtros de linha etc).

## Escopo do produto

O **Sistema de Inventário de Equipamentos de Informática (SIEI)** é um sistema que tem como objetivo centralizar e padronizar o controle de equipamentos e materiais de consumo dentro da SGTI do Empreender Paraíba. O sistema será utilizado por funcionários/estagiários da própria SGTI, incluindo também a própria responsável pelo setor, que necessitam ter mais controle e precisão no gerenciamento destes equipamentos.

---

# Posicionamento

## Oportunidade de negócios

O **Sistema de Inventário de Equipamentos de Informática (SIEI)** apresenta várias oportunidades de negócios, tais como:

1. **Consultoria e treinamento**: oferecer serviços de consultoria e treinamento para ajudar os usuários a maximizar o uso do SIEI. A equipe responsável pelo SIEI pode prestar suporte na configuração inicial, personalização do sistema para atender às necessidades específicas da SGTI e oferecer treinamento contínuo aos usuários para garantir uma utilização eficiente do sistema.
2. **Disponibilizar um funcionário (PO) para atuar internamente**: disponibilizar um funcionário para atuar presencialmente no Empreender PB, juntamente com os funcionários da SGTI. O funcionário em questão atuaria como um PO e ajudaria a equipe de desenvolvimento do SIEI a implementar novas funcionalidades com mais rapidez e eficiência, de acordo com as demandas internas da SGTI.
3. **Parcerias estratégicas**: o SIEI pode formar parcerias com fornecedores de equipamentos e materiais de Informática, permitindo que as secretarias façam aquisições diretamente através do sistema. Essas parcerias podem incluir descontos ou condições especiais para compras realizadas por meio do SIEI.
4. **Serviços de manutenção no sistema**: a equipe do SIEI pode oferecer um serviço adicional de monitoramento e manutenção do sistema.
5. **Integração com a GLPI**: o SIEI pode ser integrado com a GLPI, visando alcançar uma gestão ainda mais centralizada e eficiente, facilitando o fluxo de informações entre diferentes aplicações.
6. **Expansão para outros setores do Empreender PB**: a equipe do SIEI pode implementar e configurar a aplicação para outros setores que tenham interesse em fazer uso do software. Neste caso, algumas adaptações seriam feitas para atender as especificidades de cada setor.
7. **Expansão para o setor privado**: embora inicialmente desenvolvido para uso governamental, o SIEI pode ser adaptado e comercializado para empresas privadas que também necessitem de um sistema para inventariar e gerenciar seus respectivos equipamentos de informática.

## Descrição dos benefícios para os clientes e dos problemas resolvidos

| Benefícios                    | Problemas resolvidos                                                    | Afetados                                   |
| ----------------------------- | ----------------------------------------------------------------------- | ------------------------------------------ |
| Facilidade no gerenciamento | Dificuldade em gerenciar os equipamentos por meio de diversas ferramentas | Funcionários da SGTI, gestor |
| Otimização do tempo gasto para inventariar e consultar os equipamentos | Tempo e esforço para gerenciar e realizar consultas no inventário | Funcionários da SGTI, gestor |
| Consistência dos registros de equipamentos | Inconsistência nos registros devido ao uso de diversas ferramentas | Funcionários da SGTI |
| Melhoria no planejamento | Dificuldade em prever a necessidade de adquirir novos equipamentos/materiais | Gestor |

---

# Descrição dos stakeholders e dos usuários

Esta seção descreve os stakeholders e os usuários do **Sistema de Controle de Garantias de Produtos (SCGP).**

## Stakeholders

Segue abaixo a lista de stakeholders.

| Stakeholder                            | Descrição                                                                                                                                               | Papel                                                           |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Gestor | Pessoa responsável pela SGTI que irá determinar quem e quais funcionalidades do sistema os funcionários do setor poderão utlizar. Além disto, também será responsável por decisões relacionadas à aquisições de novos equipamentos/materiais | Administrar os acessos e permissões para realizar operações mais críticas (como remoção ou atualização). Realizar aquisição de novos equipamentos/materiais |
| Usuários | Pessoas do setor que irão utilizar o SIEI para manter o inventário da secretaria atualizado e para realizar consultas | Usuário do sistema
| Equipe de Suporte | Profissionais responsáveis por fornecer suporte aos usuários do SIEI | Fornecer suporte em relação ao SIEI e suas respectivas funcionalidades |
| Equipe de Desenvolvimento | Profissionais responsáveis por desenvolver e manter o sistema. | Desenvolvedores |
| Gerente de projeto | Profissional responsável por gerenciar o projeto e garantir que o sistema seja entregue dentro do prazo e orçamento definidos. | Gerente de projeto |

## Usuários e atores

Segue tabela com os usuários e atores do sistema:

| Usuário                  | Descrição                                                                                                    | Responsabilidades                                                                                                                                                                                                                | Stakeholders                                                                                    |
| ------------------------ | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Gestor da SGTI | Pessoa que utilizará o sistema com maior ênfase em tarefas administrativas e de gestão do próprio setor | Acompanhar diariamente a quantidade de equipamentos no inventário. Delegar quais funcionários podem ou não ter permissão para desempenhar funcionalidades mais críticas. | Gestor, Usuário |
| Clientes | Pessoas que utilizam o sistema para manter o inventário atualizado e/ou realizar consultas. | Registrar os equipamentos de informática e de consumo adquiridos. Atualizar a quantidade, situação, localização e demais informações acerca dos equipamentos. Realizar consultas. | Usuário |
| Atendente de suporte | Profissional responsável por atender os clientes e fornecer suporte em relação ao uso do sistema. | Atender as solicitações dos clientes relacionadas ao registro de equipamentos e demais funcionalidades do SIEI. | Equipe de Suporte, Usuários |
| Product Owner | Profissional que entende das regras de negócio da SGTI e que auxilia a equipe de desenvolvimento do SIEI. | Acompanhar a rotina dos funcionários da SGTI. Repassar demandas da SGTI para a equipe de desenvolvimento. Auxiliar a equipe de desenvolvimento na implementação de novas funcionalidades | Equipe de Desenvolvimento, Usuários |
| Administrador do Sistema | Profissional responsável por realizar backups, gerenciar e manter o sistema. | Realizar backup dos dados, gerenciar os usuários do sistema, atualizar o sistema e garantir o seu funcionamento adequado. | Equipe de Desenvolvimento, Gerente de Projeto                                                   |

---

TODO # Descrição do ambiente de uso

## Ambiente de uso

A seguir, são descritos alguns ambientes em que o sistema pode ser utilizado:

1. **Ambiente do Cliente**: Neste ambiente, o sistema é utilizado pelos clientes para controlar os equipamentos adquiridos. Os clientes podem acessar o sistema através de um navegador web em seus dispositivos mobile ou desktop. O navegador web poderá ser o Google Chrome, Mozilla Firefox ou Microsoft Edge com acesso através do endereço web https://www.empreender.pb.gov.com.br/siei/login. O ambiente do cliente é acessado através da internet e requer um login e senha de acesso.
2. **Ambiente Administrativo:** Neste ambiente, o sistema é utilizado pelos administradores do sistema para gerenciar e manter o sistema. Os administradores podem acessar o sistema através de um navegador web em um computador, e possuem acesso a recursos de gerenciamento, como gerenciamento de usuários, backup dos dados, e atualização do sistema.
3. **Ambiente de Teste:** Neste ambiente, o sistema é utilizado para testar novas funcionalidades e correções de bugs antes de serem disponibilizadas para os usuários finais. O ambiente de teste é acessado através de um navegador web em um computador, e requer um login e senha de acesso específicos para o ambiente de teste.

## Necessidades principais quanto ao ambiente

A seguir, é apresentada uma tabela que descreve as necessidades dos clientes com relação à qualidade, desempenho, segurança, usabilidade e confidencialidade do sistema SIEI, juntamente com sua prioridade, interesse, solução atual e soluções propostas:

| Necessidade                                                                                                                                              | Prioridade | Interesse                                                                                                                                                | Solução Atual                                                                                                                 | Soluções Propostas                                                                                                                                                                                                                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Qualidade:** O sistema deve ser confiável e livre de erros, bugs e falhas.                                                                             | Alta       | Os usuários esperam que o sistema funcione corretamente e não apresente problemas que possam prejudicar o controle dos equipamentos e materiais de consumo.                    | Testes manuais realizados pela equipe de desenvolvimento.                                                                     | Implementar testes automatizados e processos de garantia de qualidade para identificar e corrigir erros e bugs.                                                                                                                                                          |
| **Desempenho:** O sistema deve ter um bom desempenho, com tempo de resposta rápido e sem atrasos significativos.                                         | Alta       | Os usuários esperam que o sistema responda rapidamente às suas solicitações e não apresente atrasos.                                                     | Servidor dedicado para hospedagem do sistema e monitoramento constante do desempenho.                                         | Melhorar a arquitetura do sistema para garantir melhor desempenho e escalabilidade, bem como otimizar consultas de banco de dados e uso de recursos do sistema.                                                                                                          |
| **Escalabilidade:** O sistema deve ter capacidade para suportar o aumento dos usuários e dos tipos de equipamentos/materiais de consumo.                                         | Alta       | Os usuários esperam que o sistema continue funcionando de forma confiável e sem atrasos, mesmo com um grande número de usuários e equipamentos/materiais de consumo registrados. | Arquitetura escalável, com distribuição de carga e uso de servidores em nuvem.                                                | Implementar arquitetura em nuvem e balanceamento de carga para garantir a escalabilidade do sistema.                                                                                                                                                                     |
| **Segurança:** O sistema deve ser seguro, protegido contra acesso não autorizado, invasões e roubo de dados.                                             | Alta       | Os usuários esperam que suas informações estejam seguras e protegidas contra invasões e acesso não autorizado.                                           | Autenticação de usuários com login e senha, criptografia de dados sensíveis e acesso restrito somente a usuários autorizados. | Implementar medidas adicionais de segurança, como autenticação de dois fatores, certificados SSL e criptografia avançada.                                                                                                                                                |
| **Usabilidade:** O sistema deve ser fácil de usar e entender, com uma interface intuitiva e amigável ao usuário.                                         | Moderada   | Os usuários esperam que o sistema seja fácil de usar e entender, sem a necessidade de treinamento especializado.                                         | Interface de usuário simples e intuitiva.                                                                                     | Realizar testes de usabilidade com usuários reais para identificar áreas de melhoria e implementar melhorias na interface do usuário.                                                                                                                                    |
| **Tempo de resposta:** O sistema deve ter um tempo de resposta rápido para que os usuários possam consultar os equipamentos/materiais de consumo de forma eficiente. | Moderada   | Os usuários esperam que o sistema responda às suas solicitações rapidamente para que possam gerenciar os equipamentos/materiais da secretaria de forma mais eficiente.            | Monitoramento constante do tempo de resposta do sistema.                                                                      | Realizar otimizações de performance, como o uso de cache, e garantir que o sistema esteja sempre atualizado para obter um tempo de resposta rápido.                                                                                                                      |
| **Confidencialidade:** O sistema deve proteger a privacidade e confidencialidade das informações dos usuários e dos equipamentos.                                           | Alta       | Os usuários esperam que suas informações sejam mantidas em sigilo e protegidas contra acesso não autorizado.                                             | Controles de acesso restrito, criptografia de dados sensíveis e monitoramento constante das atividades do usuário.            | Realizar auditorias de segurança e implementar medidas adicionais de privacidade e proteção de dados, como política de privacidade clara e concisa, consentimento explícito do usuário para coleta e uso de dados, e implementação de protocolos de segurança avançados. |

---

# Visão geral do produto

## Visão geral

O sistema SIEI é um sistema para inventariar equipamentos de TI, que permite que os clientes possam gerenciar os equipamentos de informática e de consumo do Empreender PB. O sistema permite que os clientes registrem, atualizem e consultem os equipamentos. Os clientes também podem solicitar suporte técnico ou a implementação de novas funcionalidades.

Como o sistema SIEI é um software, a estrutura operacional é baseada em infraestrutura de TI, em vez de hardware específico. Portanto, a infraestrutura necessária para operar o sistema SIEI inclui servidores, banco de dados e dispositivos de rede, como roteadores e switches.

O sistema SIEI pode ser acessado por meio de dispositivos que possuam um navegador web e acesso à Internet, como computadores, laptops, tablets e smartphones. Isso permite que os clientes acessem e consultem o inventário de qualquer lugar e a qualquer momento.

A interação entre os dispositivos ocorre por meio de uma conexão de rede, geralmente a Internet. O servidor que hospeda o sistema SIEI se comunica com os dispositivos dos clientes por meio de solicitações HTTP e respostas, permitindo que o sistema exiba informações e interaja com o usuário.

Além disso, o sistema SIEI pode ser integrado com outros sistemas, como a própria GLPI, que já é utilizada na secretaria, e por meio de APIs (Application Programming Interface), permitindo a troca de informações entre os sistemas de forma automatizada.

## Custo e venda

Os custos e a venda do software serão definidos em conformidade com as condições estabelecidas no edital, garantindo que o valor seja justo e compatível com o orçamento previsto.

Os cálculos dos custos incluirão não apenas o desenvolvimento e a implementação da solução, mas também os gastos com manutenção, suporte técnico, e eventuais atualizações.

A venda do software, assim como os termos de pagamento, serão regidos pelas cláusulas do edital, assegurando transparência no processo de contratação e cumprimento das obrigações financeiras por ambas as partes. Eventuais ajustes de preço ou condições adicionais também seguirão as diretrizes contratuais estabelecidas.

## Licenciamento e instalação

O licenciamento e a instalação do software serão realizados em conformidade com as normas estabelecidas no edital, respeitando as diretrizes de propriedade intelectual e distribuição previstas.

A solução será implementada de acordo com as especificações técnicas fornecidas, garantindo a adequação aos padrões de uso definidos pela administração municipal.

O processo de instalação abrangerá a configuração adequada dos ambientes operacionais e a entrega das chaves de licenciamento, conforme requerido. Qualquer ajuste ou configuração adicional será executado em conformidade com os procedimentos descritos no edital, assegurando a conformidade com as políticas de segurança e manutenção contínua.

## Características e funcionalidades de alto nível

Esta seção define e descreve as características do SIEI. Trata-se dos
requisitos de alto nível do sistema que são necessários para propiciar benefícios aos usuários.

1. O sistema deve permitir o cadastro de equipamentos e materiais de consumo, incluindo informações sobre modelo, marca, quantidade, tipo de equipamento/material e data de aquisição. No caso dos equipamentos, além dessas informações, os dados a seguir também devem ser informados: patrimônio, número de série, endereço IP, MAC, situação do equipamento, funcionário responsável, setor onde o equipamento está alocado e a data que a garantia do equipamento expirará.
1. O sistema deve permitir que os dados de um determinado registro de equipamento/material de consumo possa ser alterado, respeitando as regras determinadas pela gestora da SGTI.
1. O sistema deve oferecer funcionalidades de consulta avançada, permitindo a pesquisa de equipamentos por critérios como patrimônio, número de série, situação do equipamento, funcionário responsável, etc.
1. O sistema deve oferecer funcionalidades de consulta avançada, permitindo a pesquisa de materiais de consumo por critérios como marca, modelo, tipo de material, etc.
1. O sistema deve permitir a configuração de permissões de acesso, definindo quais usuários podem realizar operações específicas, como adicionar, editar ou remover itens do inventário.
1. O sistema deve permitir a exclusão de um determinado registro, desde que respeite as regras determinadas pela gestora da SGTI.
1. O sistema deve possibilitar a atualização em tempo real das informações a respeito dos equipamentos e materiais de consumo.
1. O sistema deve manter um histórico completo de movimentações dos equipamentos, registrando todas as alterações de localização, status, responsável e data em que a mudança em questão foi realizada.
1. O sistema deve enviar notificações aos usuários quando a garantia de um equipamento de Informática estiver próxima do vencimento, para que o equipamento em questão possa ser testado e, caso algum problema seja identificado, a garantia possa ser devidamente utilizada.
1. O sistema deve enviar notificações aos usuários quando um determinado equipamento de consumo estiver se esgotando. Deste modo, a gestora da SGTI poderá fazer a solicitação deste material antes de que algum setor da secretaria possa ser afetado.
1. O sistema deve realizar backups automáticos periódicos para garantir a segurança dos dados e facilitar a recuperação em caso de falhas.
1. O sistema deve permitir a exportação de dados do inventário para formatos como CSV ou PDF, facilitando o compartilhamento e a análise interna.
1. O sistema deve permitir o registro de novos usuários, com diferentes níveis de permissão de acesso, desde administradores até usuários comuns.
1. O sistema deve garantir a segurança das informações dos usuários, equipamentos e materiais de consumo, com acesso restrito e controle de permissões de usuários.
1. O sistema deve ter uma interface de usuário amigável e de fácil utilização, para que os usuários possam utilizar as funcionalidades sem dificuldade.
1. O sistema deve ter um desempenho satisfatório, com tempos de resposta rápidos e sem interrupções ou falhas.
1. O sistema deve ter escalabilidade, para que possa ser adaptado às necessidades de novos usuários, equipamentos e materiais de consumo, sem prejudicar o desempenho e a qualidade.
1. O sistema deve ser desenvolvido em conformidade com as normas e padrões de qualidade estabelecidos para o desenvolvimento de software.
1. O sistema deve ser documentado e ter seu código-fonte disponível para auditoria e manutenção futura.

## Restrições

Algumas possíveis restrições que podem ser aplicadas ao sistema são:

1. **Restrição de orçamento:** O projeto deve ser concluído dentro de um determinado orçamento e não pode excedê-lo.
2. **Restrição de tempo:** O sistema deve ser desenvolvido e implementado dentro de um prazo específico e não pode ser estendido, conforme negociado com o cliente, em até um ano, possuindo entregas quinzenais de um produto mínimo viável (MVP).
3. **Restrições de hardware:** O sistema deve ser capaz de funcionar em uma determinada configuração de hardware atual e não pode ser executado em sistemas mais antigos.
4. **Restrições de segurança e privacidade:** O sistema deve atender aos requisitos de segurança, privacidade e proteção de dados do usuário, conforme a Lei Geral de Proteção de Dados (LGPD).
5. **Restrições de usabilidade:** O sistema deve ser fácil de usar e acessível para usuários com deficiências visuais e motoras.
6. **Restrições de interoperabilidade**: O sistema deve ser capaz de interoperar com outros sistemas e aplicativos.
7. **Restrições de desempenho**: O sistema deve atender aos requisitos de desempenho, como velocidade, escalabilidade e disponibilidade.
8. **Restrições geográficas**: O sistema deve ser compatível com os requisitos geográficos, como fusos horários e os idiomas inglês, espanhol e português.

---

Data: 28 de agosto de 2024

**Validado por:**

<address>
Caio Bernadelli, Felipe Cartaxo, Gabriel Oliveira, Michel Lavanere, Sheila Lee | Equipe de Desenvolvimento do SIEI
Empresa.com<br>
Box 564, João Pessoa<br>
BRA
</address>

---
Criado em Agosto de 2024 pela _Equipe de Desenvolvimento do SIEI_ -->
