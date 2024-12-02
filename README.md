<h1>Visão do Produto</h1>

<h2>Sistema de Recrutamento e Seleção - ContratAe</h2>

<small>Versão 1.0</small>

---

## Histórico de revisões

|    Data    | Versão |           Descrição           |      Autor       |
| :--------: | :----: | :---------------------------: | :--------------: |
| 02/12/2024 |  1.0   |     Criação do documento      |    João Vittor   |
| 02/12/2024 |  1.0   |     Criação do documento      |    Kauã Victor   |
| 02/12/2024 |  1.0   |     Criação do documento      |    Lucas Kaique  |
| 02/12/2024 |  1.0   |     Criação do documento      |    Silas Leão    |

---

## Sumário

- [Introdução](#introdução)
  - [Propósito](#propósito)
  - [Definições e abreviações](#definições-e-abreviações)
    - [Abreviações](#abreviações)
    - [Definições](#definições)
  - [Escopo do produto](#escopo-do-produto)
- [Posicionamento](#posicionamento)
  - [Serviços disponíveis](#serviços-disponíveis)
  - [Descrição dos benefícios para os usuários e dos problemas resolvidos](#descrição-dos-benefícios-para-os-usuários-e-dos-problemas-resolvidos)
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

O objetivo deste documento é coletar, analisar e definir características e as necessidades de alto nível do **Sistema de Recrutamento e Seleção - ContratAe**

Ele se concentra nos recursos necessários aos stakeholders e aos usuários, e nas razões que levam a essas necessidades.

Os detalhes de como o **Sistema de Recrutamento e Seleção - ContratAe** atingem essas necessidades são descritos nas _especificações de casos de uso_ e nos _requisitos funcionais_.

## Definições e abreviações

### Abreviações

| Termo | Definição                                    |
| :---: | -------------------------------------------- |
|  DVP  | Documento de Visão do Produto                |
|  AWS  | Amazon Web Service                           |

### Definições

|    Termo    | Definição                                                                                                                       |
| :---------: | ------------------------------------------------------------------------------------------------------------------------------- |
|  Candidato  | É uma pessoa da área de tecnologia que busca vagas de emprego.                                                                  |
|  Recrutador | É uma pessoa a mando de uma empresa em busca de candidatos para preecherem uma vaga.                                            |
|    Vaga     | É uma oportunidade de emprego postada pelo recrutador.                                                                          |
| Candidatura | É uma ação que o candidato faz para demonstrar interesse em uma vaga.                                                           |

## Escopo do produto

O **Sistema de Recrutamento e Seleção - ContratAe** é um sistema que tem como objetivo conectar candidatos da área de tecnologia as melhores vagas do mercado. Será usada por candidatos que buscar uma nova oportunidades e por recrutadores em busca de talentos.
---

# Posicionamento

## Serviços disponíveis.

O **Sistema de Recrutamento e Seleção - ContratAe** apresenta várias oportunidades de conectar talentos com empresas, tais como:

1. **Serviço de assinatura**: oferece aos candidatos um serviço de assinatura, onde eles possam pagar uma taxa mensal para ter acesso ao ContratAe. Os candidatos poderão destacar seu perfil para facilitar o match com os recrutadores.
2. **Promoção de vagas**: os recrutadores poderão promover vagas para que elas tenham destaque nas buscas realizadas pelos candidatos.
3. **Parcerias com empresas**: o ContratAe oferece programas de bolsas de estudo em parceria com empresas para capacitar candidatos para o mercado de trabalho. 
4. **Expansão para outros mercados**: o ContratAe atualmente opera apenas no setor tecnológico, mas os serviços podem ser expandidos para outras áreas.

## Descrição dos benefícios para os usuários e dos problemas resolvidos

| Benefícios                               | Problemas Resolvidos                                                                                       | Afetados                                   |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| Facilidade de conexão com recrutadores   | Dificuldade de encontrar vagas.                                                                            | Candidatos que buscam vagas de emprego     |
| Facilidade de conexão com candidatos     | Dificuldade dos recrutadores em encontrar o candidato ideal para a vaga.                                   | Recrutadores que postam vagas              |
| Melhor experiência de candidatura        | Uso de sites terceiros para envio de currículos.                                                           | Candidatos que buscam vagas de emprego     |
| Economia de tempo e maior alcance        | Os candidatos irem até um espaço físico para entregar currículo e serem limitados a empresas locais.       | Candidatos que buscam vagas de emprego     |

---

# Descrição dos stakeholders e dos usuários

Esta seção descreve os stakeholders e os usuários do **Sistema de Recrutamento e Seleção - ContratAe.**

## Stakeholders

Segue abaixo a lista de stakeholders.

| Stakeholder                            | Descrição                                                                                                                                               | Papel                                                           |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Candidato                              | Pessoas interessadas em encontrar vagas de emprego na área de tecnologia.                                                                               | Usuário do sistema                                              |
| Equipe de Desenvolvimento              | Profissionais responsáveis por desenvolver e manter o sistema.                                                                                          | Desenvolvedores                                                 |
| Gerente de Projeto                     | Profissional responsável por gerenciar o projeto e garantir que o sistema seja entregue dentro do prazo e orçamento definidos.                          | Gerente de Projeto                                              |
| Recrutador                             | Profissionais responsáveis por encontrar talentos para as vagas.                                                                                        | Postar vagas e selecionar os candidatos                         |
| Empresa                                | Entidade interessada na contratação e capacitação de profissionais.                                                                                     | Oferecer vagas e treinamentos                                   |

## Usuários e atores

Segue tabela com os usuários e atores do sistema:

| Usuário                  | Descrição                                                                                                    | Responsabilidades                                                                                                                                                                                                                | Stakeholders                                                                                    |
| ------------------------ | ------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Candidato                | Pessoas que buscam e se candidatam para vagas.                                                               | Registrar suas informações de contato e profissionais para a criação de um perfil na plataforma e poder realizar candidaturas.                                                                                                   | Equipe de Desenvolvimento, Recrutador, Empresa                                                  |
| Recrutador               | Pessoas que postam vagas e encontram candidatos                                                              | Registrar informações da empresa que trabalha, postar vagas, encontrar candidatos.                                                                                                                                               | Equipe de Desenvolvimento, Candidato, Empresa                                                   |
| Atendente de Suporte     | Profissional responsável por atender os clientes e fornecer suporte em relação ao uso do sistema.            | Atender as solicitações dos usuários relacionadas às assinaturas e vagas promovidas no sistema.                                                                                                                                  | Equipe de Desenvolvimento, Candidato, Recrutador                                                |
| Administrador do Sistema | Profissional responsável por gerenciar e manter o sistema.                                                   | Gerenciar os usuários do sistema, realizar backup dos dados, atualizar o sistema e garantir o seu funcionamento adequado.                                                                                                        | Equipe de Desenvolvimento, Gerente de Projeto, Candidato, Recrutador                            |

---

# Descrição do ambiente de uso

## Ambiente de uso

A seguir, são descritos alguns ambientes em que o sistema pode ser utilizado:

1. **Ambiente do Candidato**: Neste ambiente, o sistema é utilizado pelos candidatos para cadastrar suas informações, buscar vagas e se candidatar. Os usuários podem acessar o sistema através de dispositivos móveis, como smartphones e tablets através de um navegador web em seus computadores. O navegador web poderá ser o Google Chrome, Mozilla Firefox ou Microsoft Edge com acesso através do endereço web <https://www.contratae.com.br>.
2. **Ambiente do Recrutrador**: Neste ambiente, o sistema é utilizado pelos recutadores para cadastrar vagas, visualizar perfis dos candidatos e selecionar os que se qualificam.
3. **Ambiente Administrativo:** Neste ambiente, o sistema é utilizado pelos administradores do sistema para gerenciar e manter o sistema. Os administradores podem acessar o sistema através de um navegador web em um computador, e possuem acesso a recursos de gerenciamento, como gerenciamento de usuários, backup dos dados, e atualização do sistema.
4. **Ambiente de Teste:** Neste ambiente, o sistema é utilizado para testar novas funcionalidades e correções de bugs antes de serem disponibilizadas para os usuários finais. O ambiente de teste é acessado através de um navegador web em um computador.

## Necessidades principais quanto ao ambiente

A seguir, é apresentada uma tabela que descreve as necessidades dos clientes com relação à qualidade, desempenho, segurança, usabilidade e confidencialidade do sistema SCGP, juntamente com sua prioridade, interesse, solução atual e soluções propostas:

| Necessidade                                                                                                                                              | Prioridade | Interesse                                                                                                                                                | Solução Atual                                                                                                                 | Soluções Propostas                                                                                                                                                                                                                                                       |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Qualidade:** O sistema deve ser confiável e livre de erros, bugs e falhas.                                                                             | Alta       | Os usuários esperam que o sistema funcione corretamente e não apresente problemas que possam prejudicar as candidaturas                                  | Testes manuais realizados pela equipe de desenvolvimento.                                                                     | Implementar testes automatizados e processos de garantia de qualidade para identificar e corrigir erros e bugs.                                                                                                                                                          |
| **Desempenho:** O sistema deve ter um bom desempenho, com tempo de resposta rápido e sem atrasos significativos.                                         | Alta       | Os usuários esperam que o sistema responda rapidamente às suas solicitações e não apresente atrasos.                                                     | AWS para hospedagem do sistema e monitoramento constante do desempenho.                                                       | Melhorar a arquitetura do sistema para garantir melhor desempenho e escalabilidade, bem como otimizar consultas de banco de dados e uso de recursos do sistema.                                                                                                          |
| **Escalabilidade:** O sistema deve ter capacidade para suportar o crescimento do número de usuários e vagas.                                             | Alta       | Os usuários esperam que o sistema continue funcionando de forma confiável e sem atrasos, mesmo com um grande número de usuários e vagas registradas.     | Arquitetura escalável, com distribuição de carga e uso de servidores em nuvem.                                                | Implementar arquitetura em nuvem e balanceamento de carga para garantir a escalabilidade do sistema.                                                                                                                                                                     |
| **Segurança:** O sistema deve ser seguro, protegido contra acesso não autorizado, invasões e roubo de dados.                                             | Alta       | Os usuários esperam que suas informações estejam seguras e protegidas contra invasões e acesso não autorizado.                                           | Autenticação de usuários com login e senha, criptografia de dados sensíveis e acesso restrito somente a usuários autorizados. | Implementar medidas adicionais de segurança, como autenticação de dois fatores, certificados SSL e criptografia avançada.                                                                                                                                                |
| **Usabilidade:** O sistema deve ser fácil de usar e entender, com uma interface intuitiva e amigável ao usuário.                                         | Moderada   | Os usuários esperam que o sistema seja fácil de usar e entender, sem a necessidade de treinamento especializado.                                         | Interface de usuário simples e intuitiva.                                                                                     | Realizar testes de usabilidade com usuários reais para identificar áreas de melhoria e implementar melhorias na interface do usuário.                                                                                                                                    |
| **Tempo de resposta:** O sistema deve ter um tempo de resposta rápido para que os usuários possam acessar e controlar suas garantias de forma eficiente. | Moderada   | Os usuários esperam que o sistema responda às suas solicitações rapidamente para que possam gerenciar suas garantias de forma mais eficiente.            | Monitoramento constante do tempo de resposta do sistema.                                                                      | Realizar otimizações de performance, como o uso de cache, e garantir que o sistema esteja sempre atualizado para obter um tempo de resposta rápido.                                                                                                                      |
| **Confidencialidade:** O sistema deve proteger a privacidade e confidencialidade das informações dos usuários.                                           | Alta       | Os usuários esperam que suas informações sejam mantidas em sigilo e protegidas contra acesso não autorizado.                                             | Controles de acesso restrito, criptografia de dados sensíveis e monitoramento constante das atividades do usuário.            | Realizar auditorias de segurança e implementar medidas adicionais de privacidade e proteção de dados, como política de privacidade clara e concisa, consentimento explícito do usuário para coleta e uso de dados, e implementação de protocolos de segurança avançados. |

---

# Visão geral do produto

## Visão geral

O sistema ContratAe é um sistema de recrutamento e seleção onde candidatos e recrutadores se conectam. O sistema permite que os candidatos forneçam suas informações profissionais e qualificações tecnicas, além de forncer um sistema de assinatura onde é possível ficar em destaque para facilitar a conexão com recrutadores. Os recrutadores podem postar vagas e buscar candidatos através de buscas no sistema além de promover vagas para ficarem em destaque. 

Como o sistema ContratAe é um software, a estrutura operacional é baseada em infraestrutura de TI, em vez de hardware específico. Portanto, a infraestrutura necessária para operar o sistema ContratAe inclui servidores em nuvem.

O sistema ContratAe pode ser acessado por meio de dispositivos que possuam um navegador web e acesso à Internet, como computadores, laptops, tablets e smartphones. Isso permite que os usuários acessem e controlem suas candidaturas e vagas de qualquer lugar e a qualquer momento.

## Custo e venda

Como o ContratAe é um produto independente o software não será comercializado, apenas assinaturas e serviços internos do sistema.

## Licenciamento e instalação

O sistema será aberto ao público em geral e disponibilizado através de navegadores web sem a necessidade de instalação.

## Características e funcionalidades de alto nível

Esta seção define e descreve as características do ContratAe. Trata-se dos
requisitos de alto nível do sistema que são necessários para propiciar benefícios aos usuários.

1. O sistema deve permitir o cadastro de informações dos candidatos, incluindo informações de contato e profissionais.
2. O sistema deve permitir que os recrutadores postem vagas de emprego, com descrição, cargo e salário.
3. O sistema deve permitir aos candidatos o acompanhamento do status das candidaturas.
4. O sistema deve permitir que os recrutadores tenham acesso aos perfis dos candidatos, informações como área, habilidades e contatos.
5. O sistema deve permitir que os candidatos procurem vagas apartir de um mecanismo de busca.
5. O sistema deve permitir que os candidatos demonstrem interesse em uma vaga, colocando seu perfil na vaga.
6. O sistema deve permitir que os recrutadores busquem candidatos baseado em palavras-chave.
7. O sistema deve ter escalabilidade, para que possa ser adaptado às necessidades de novos usuários e vagas, sem prejudicar o desempenho e a qualidade.
8. O sistema deve ser desenvolvido em conformidade com as normas e padrões de qualidade estabelecidos para o desenvolvimento de software.
9. O sistema deve ser documentado e ter seu código-fonte disponível para auditoria e manutenção futura.
10. O sistema deve garantir a segurança das informações dos usuários e vagas, com acesso restrito e controle de permissões.

## Restrições

Algumas possíveis restrições que podem ser aplicadas ao sistema são:

1. **Restrição de orçamento:** O projeto deve ser concluído dentro de um determinado orçamento e não pode excedê-lo.
2. **Restrição de tempo:** O sistema deve ser desenvolvido e implementado dentro de um prazo específico e não pode ser estendido, conforme estabelida pela Securitas, em até 2 anos, possuindo entregas quinzenais de um produto mínimo viável (MVP).
3. **Restrições de hardware:** O sistema deve ser capaz de funcionar em dispositivos que tem acesso a internet através de um navegador web.
4. **Restrições de segurança e privacidade:** O sistema deve atender aos requisitos de segurança, privacidade e proteção de dados do usuário, conforme a Lei Geral de Proteção de Dados (LGPD).
5. **Restrições de usabilidade:** O sistema deve ser fácil de usar e acessível para usuários com deficiências visuais e motoras.
6. **Restrições de interoperabilidade**: O sistema deve ser capaz de interoperar com outros sistemas e aplicativos.
7. **Restrições de desempenho**: O sistema deve atender aos requisitos de desempenho, como velocidade, escalabilidade e disponibilidade.
8. **Restrições geográficas**: O sistema deve ser compatível com os requisitos geográficos, como fusos horários e os idiomas inglês, espanhol e português.

---

Data: 02 de Dezembro de 2024

**Validado por:**

<address>
<a href="mailto:contato@securitas.com">João Vittor, Kauã Victor, Lucas Kaique e Silas Leão</a> | Desenvolvedores de Software<br>
contato@securitas.com<br>
Securitas.com<br>
Jaguaribe - 002, João Pessoa<br>
BRA
</address>

---
Criado em Dezembro de 2024 pela _Equipe Securitas_
