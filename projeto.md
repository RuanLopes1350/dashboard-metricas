# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Gilberto Pereira da Silva|Professor|gilberto.silva@ifro.edu.br|
|Roberto Simplicio Guimaraes|Professor|roberto.simplicio@ifro.edu.br|
|Wesley Jhonnes Ramos Rolim|Professor|wesley.rolim@ifro.edu.br|


# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO

|| |
|:---|:---|
| **NOME** |Dashboard de Métricas |
| **Membros do Projeto** | Giullia Beatriz Chiarotti - Ruan Lopes - Henrique Zorzi - Caique Yamandu - Ana Clara |
| **PRINCIPAL OBJETIVO** | Facilitar a visualização dos Projetos |
| **BENEFÍCIOS ESPERADOS** | Otimização do Tempo |
| **INÍCIO E TÉRMINO PREVISTOS** | 01/10/2024 - 11/03/2025 |


# INTRODUÇÃO

Este documento apresenta a especificação do Projeto de Software desenvolvido para facilitar a visualização e o acompanhamento de projetos acadêmicos utilizando um dashboard de métricas do GitLab. O sistema proposto permitirá a análise de dados por meio de gráficos intuitivos, proporcionando aos usuários uma visão clara sobre o progresso das atividades e a participação dos envolvidos para os gestores responsaveis.
A documentação detalha os requisitos funcionais e não funcionais, os stakeholders, a metodologia adotada, os diagramas de modelagem e demais aspectos técnicos necessários para garantir a viabilidade e a eficácia do projeto. O objetivo principal é otimizar o tempo dos usuários, oferecendo uma interface prática e eficiente para o monitoramento das informações.
Além disso, este documento busca garantir que todas as informações relevantes para o desenvolvimento e implementação do sistema estejam devidamente organizadas, permitindo uma compreensão clara de cada etapa do projeto e das decisões técnicas adotadas.


## PROPÓSITO DESTE DOCUMENTO

Garantir que todas as informações relevantes para a produção do produto final estejam organizadas para assim facilitar o entendimento do que estiver a cargo da produção!

## CONCEPÇÃO DO SISTEMA

Métodos utilizados para a obtenção dos requisitos do sistema:
  * Baseado em requisitos de Sistemas Semelhantes.


# DESCRIÇÃO GERAL
O dashboard de métricas do GitLab é uma interface visual que foi desenvolvida para exibir dados aos usuários por meio de gráficos, como por exemplo o andamento de cada projeto, quantas tarefas estão em andamento de cada projeto, o dashboard vai exibir também informações como quais usuários estão mais ativos e os inativos, o total de commits por projetos. Fornecendo uma melhor visualização dos dados e ampliando o entendimento dos usuários sobre os projetos que estão em andamento e os que já foram concluídos.

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Professores:**|será um usuário administrador, podendo ver o progresso dos projetos no qual fazem parte e também terão acesso ao progresso dos outros projetos e participantes.|



### Sistemas similares:
O dashboard vai ser baseado nos projetos desenvolvidos no GitLab, exibindo gráficos intuitivos para os usuários. Alguns exemplos similares ao dashboard de métricas são: 
•	Microsoft Power BI;
•	QilkView;
•	Google Data Studio;
•	O próprio dashboard fornecido pelo GitHub.


## Suposições e dependências

Não será necessário que os usuários tenham um computador muito potente para conseguir acessar o dashboard;
•	Por padrão o computador deve ter uma memória RAM de 4GB;
•	Um processador comum como um Intel Core I3 de 3° Geração ou mais;
•	Um navegador instalado podendo ser o Google Chrome, Microsoft Edge, etc...;
•	Conexão com a internet, preferencialmente com uma velocidade superior ou igual a 5 MB.

# ESTUDO DE VIABILIDADE

Análise de Viabilidade Técnica

Tecnologias Utilizadas:
  * Front-End: React ou Vue.js para criação da interface de usuário, garantindo uma experiência fluida e interativa.

  * Back-End: Node.js para integração com a API do GitLab, manipulando requisições e gerenciando dados.

  * Banco de Dados: A depender da necessidade de persistência de dados, pode-se utilizar MongoDB ou Postgree para armazenar dados complementares.

Integração com o GitLab:
  * A API do GitLab será usada para coletar informações sobre commits, pull requests, issues, tasks, comentários e milestones.
  * Garantir que as permissões de acesso à API sejam configuradas corretamente para extrair as informações necessárias.

Escalabilidade:
  * Dashboard será projetado para atender às necessidades atuais, com possibilidade de crescimento conforme o número de usuários e dados aumentem.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Viabilidade Econômica
  * Custos de Desenvolvimento:

   Recursos Humanos: O time é composto por 4 desenvolvedores, portanto, o custo de desenvolvimento será baseado nas horas trabalhadas.
   
   Ferramentas: Caso seja necessário adquirir ferramentas específicas para a integração ou visualização de dados (plano pró Power Bi), serão considerados custos adicionais.
  
  * Infraestrutura: O uso de servidores e bancos de dados será feito dentro da infraestrutura do instituto, o que pode reduzir os custos operacionais.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Exemplo de Estimativa de Custos:
  * 4 desenvolvedores x 6 meses de trabalho x custo médio:
  * 2.400 x 4 x 6 = 57.600.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Viabilidade Operacional:
  * Equipe de Manutenção: Como é um projeto interno, a equipe de desenvolvedores será responsável pela manutenção durante o período inicial após o lançamento. Após esse período, um time técnico poderá ser definido para garantir a continuidade e evolução do sistema.

  * Suporte Técnico: Os desenvolvedores estarão disponíveis para resolver bugs e implementar melhorias conforme necessário.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Viabilidade Legal
  * Licenciamento e Direitos: A API do GitLab será utilizada dentro dos limites definidos pela documentação oficial, garantindo conformidade com os termos de uso. Como é um projeto interno, não há necessidade de preocupações com licenciamento externo.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Análise de Mercado:
  * Público-Alvo: Professores do instituto serão os usuários principais do dashboard. O objetivo é fornecer uma interface simples, mas poderosa, que permita aos professores acompanhar o andamento dos projetos sem a necessidade de um conhecimento técnico aprofundado.
  * Necessidade: A necessidade do dashboard surge da falta de uma visualização consolidada e de fácil acesso para os professores, permitindo que possam monitorar o progresso dos alunos e das atividades em tempo real.
  * Concorrência: Existem opções concorrentes que possuem funcionalidade semelhante e até idêntica, mas são opções pagas, portanto ao menos internamente, o risco de concorrência é baixo para nulo.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Riscos e Mitigações:
  * Dependência de API: Se a API do GitLab sofrer alterações inesperadas ou ficar indisponível, será necessário implementar mecanismos de fallback ou notificações para os usuários sobre a indisponibilidade.
  * Falta de Adoção: Se os professores não se familiarizarem com o uso do dashboard, será importante oferecer treinamentos ou tutoriais rápidos para facilitar a integração.
  * Excesso de Dados: O dashboard pode se tornar sobrecarregado se muitos dados forem puxados de uma vez. A mitigação pode ser feita através de filtros e paginamento dos dados.


# Metodologia Adotada no Desenvolvimento

A metodologia de desenvolvimento escolhida foi a Kanban, utilizada para gerenciar o fluxo de trabalho do projeto de software. O objetivo é garantir transparência, melhoria contínua e eficiência no processo de desenvolvimento.

**Princípios do Kanban**

O Kanban segue os seguintes princípios:
  * Visualizar o fluxo de trabalho: Uso de um quadro Kanban para acompanhar as tarefas.
  * Limitar o trabalho em progresso (WIP): Definição de limites para evitar sobrecarga.
  * Gerenciar o fluxo: Otimizar a eficiência do time.
  * Tornar explícitas as regras do processo: Definição clara das regras de trabalho.
  * Implementar ciclos de feedback: Reuniões periódicas para melhoria contínua.
  * Melhorar continuamente: Ajustes baseados em feedback e análises.

O quadro Kanban utilizado no projeto contém as seguintes colunas:
  * Aberto: Lista de tarefas a serem desenvolvidas.
  * Fazendo: Tarefas em desenvolvimento.
  * Fechado: Tarefas finalizadas e entregues.

Regras e Políticas do Fluxo de Trabalho
  * Cada tarefa deve ter um responsável atribuído.
  * As tarefas devem seguir o fluxo de trabalho do quadro Kanban.
  * Merge requests devem ser revisados por pelo menos um membro da equipe antes da aprovação.
  * Reuniões semanais para revisão do progresso e ajustes no processo.

Métricas e Monitoramento
Para acompanhar a eficiência do time, utilizamos as seguintes métricas:
  * Lead Time: Tempo total desde a criação da tarefa até sua conclusão.
  * Cycle Time: Tempo que uma tarefa leva desde o início do desenvolvimento até a conclusão.
  * Throughput: Quantidade de tarefas concluídas em um período.


# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 |Coleta de Dados via API do GitLab|• Implementar a coleta de commits por usuário, merge requests, issues, milestones, comentários e discussões, estatísticas de código, e labels. •	Utilizar endpoints específicos para cada métrica.|
|RF-002 |Coleta de Dados via Terminal|•	Implementar scripts para coletar dados como linhas de código adicionadas/removidas, análise de blame, histórico detalhado de commits, churn de código e complexidade de código.|
|RF-003 |visualização de Dados|• Criar gráficos de barras, linhas, pizza, burndown, tabelas dinâmicas, heatmaps, gráficos de dispersão e dashboards interativos.• Assegurar que as visualizações suportem metodologias Kanban e Scrum.|
|RF-004 |Construção do Dashboard|• Integrar dados coletados em um banco de dados ou em arquivos estruturados (JSON, CSV). • Utilizar ferramentas como Grafana, Tableau, PowerBI ou D3.js para visualizações.|
|RF-005 |Adaptação para Metodologias Ágeis|• Implementar funcionalidades específicas para Scrum, como gráficos de velocity, burnup e backlog health. • Implementar funcionalidades para Kanban, como Cumulative Flow Diagrams, lead time, cycle time e Work in Progress (WIP).|
|RF-006 |Interatividade e Personalização|• Permitir que os usuários filtrem e interajam com os dados. • Oferecer opções de customização do dashboard conforme as necessidades do projeto e da equipe.|
|RF-007 |Alertas e Notificações|•	Configurar alertas para métricas críticas, como aumento no número de issues abertas.|



## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
RNF-001 |Performance|• O dashboard deve atualizar e exibir dados em tempo real ou em intervalos regulares sem atrasos perceptíveis.|
RNF-002 |Escalabilidade|• A arquitetura deve suportar um aumento no volume de dados e usuários sem degradação de desempenho.|
RNF-003 |Segurança|• Os dados devem ser protegidos contra acesso não autorizado, garantindo autenticação e autorização adequadas.|
RNF-004 |Usabilidade|• A interface deve ser intuitiva e fácil de usar para todos os stakeholders, com suporte a acessibilidade.|
RNF-005 |Confiabilidade|• O sistema deve ser robusto e resiliente a falhas, garantindo alta disponibilidade.|
RNF-006 |Compatibilidade|• O dashboard deve ser compatível com diferentes navegadores e dispositivos, assegurando uma experiência consistente.|
RNF-007 |Manutenibilidade|• O código deve ser bem documentado e estruturado para facilitar a manutenção e futuras atualizações.|


# Prototipagem

![Login](/images/Figma/Login.png)
![Dashboard](/images/Figma/Dashboard.png)
![Projetos](/images/Figma/Projetos.png)
![Projetos Expandido](/images/Figma/Projetos-1.png)
![Participantes](/images/Figma/Participantes.png)
![Commits](/images/Figma/Commits.png)
![Issues](/images/Figma/Issues.png)
![Merge Requests](/images/Figma/Marge_Requests.png)
![Perfil](/images/Figma/Perfil.png)
![Configurações](/images/Figma/Configura%C3%A7%C3%B5es.png)


# Diagrama de Casos de Uso

![Diagrama Casos de Uso](/images/Dashboard_-_Diagrama_de_Caso_de_Uso__ofc_.jpg)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Realizar Login

|UC-01 - Realizar Login|           
|:---|
|**Descrição/Objetivo:** Permitir que os usuários do sistema (alunos e professores) acessem o dashboard de métricas do GitLab por meio de autenticação|
|**Atores: Professor**|
|**Pré-condições:** O usuário deve estar cadastrado no sistema e o usuário deve possuir um navegador compatível e conexão com a internet.|
|**Pós-condições:** O usuário terá acesso ao dashboard e às funcionalidades conforme seu nível de permissão.|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário acessa a página de login do sistema. |
|2. O sistema exibe os campos para inserção de credenciais (e-mail e senha).|
|3. O usuário insere suas credenciais e confirma o login.|
|4. O sistema valida as credenciais e autentica o usuário.|
|5. O usuário é redirecionado para o dashboard correspondente ao seu perfil (aluno ou professor).|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Usuário insere credenciais inválidas** |
|1. O sistema informa que o e-mail ou senha estão incorretos
|2. O usuário pode tentar novamente ou utilizar a opção de recuperação de senha.|
|**A2:  Usuário esqueceu a senha** |
|1. O usuário seleciona a opção "Esqueci minha senha".|
|2. O sistema solicita o e-mail cadastrado.|
|3. O usuário insere o e-mail e confirma.|
|4. O sistema envia um link de recuperação de senha para o e-mail informado.|
|5. O usuário redefine a senha e tenta realizar login novamente.|

### UC-02 - Visualizar Elementos do Sistema

|UC-02 - Visualizar Elementos do Sistema|           
|:---|
|**Descrição/Objetivo:** Permitir que os usuários do sistema visualizem os elementos e métricas exibidas no dashboard, como commits, tarefas em andamento, issues, participantes ativos, histórico de alterações e gráficos estatísticos.|
|**Atores: Professor**|
|**Pré-condições:** O usuário deve estar autenticado no sistema e o sistema deve estar conectado à internet para carregar as métricas em tempo real.|
|**Pós-condições:** O usuário pode visualizar e interpretar as métricas apresentadas no dashboard e o sistema exibe as informações atualizadas e organizadas de maneira intuitiva.|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário acessa o sistema e entra no dashboard. |
|2. O sistema carrega e exibe os elementos disponíveis, como:
 - Total de commits e commits por projetos.
 - Tarefas em andamento e tarefas em atraso.
 - Participantes mais ativos e com poucas atividades.
 - Relatórios de issues e histórico de alterações.
 - Merge requests e últimos commits.
 - Projetos mais atualizados e milestones.|
|3. O usuário pode rolar a tela para visualizar mais informações e métricas.|
|4. O usuário pode clicar em "Ver tudo" para expandir determinadas seções.|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Falha na conexão com a internet** |
|1. O sistema exibe uma mensagem informando que os dados não puderam ser carregados.|
|2. O usuário pode tentar recarregar a página quando a conexão for restabelecida.|
|**A2:  Falha no carregamento de dados do GitLab** |
|1. O sistema informa que há um erro na sincronização com o GitLab.|
|2. O usuário pode tentar novamente mais tarde ou contatar o suporte técnico.|

### UC-03 - Gerenciar Projetos

|UC-03 - Gerenciar Projetos|           
|:---|
|**Descrição/Objetivo:** Permitir que o gestor do projeto (professor) gerencie os projetos no sistema, podendo visualizar, editar e acompanhar o progresso das atividades, além de gerenciar participantes, commits, issues e milestones.|
|**Atores: Professor**|
|**Pré-condições:** O usuário deve estar autenticado no sistema e o usuário deve ter permissão de administrador para gerenciar projetos.|
|**Pós-condições:** As informações do projeto são atualizadas conforme as ações do gestor.|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O gestor acessa o sistema e entra na seção "Projetos".|
|2. O sistema exibe a lista de projetos disponíveis.|
|3. O gestor seleciona um projeto para visualizar os detalhes.|
|4. O sistema exibe as informações do projeto, incluindo: Commits, issues, merge requests e tarefas em andamento, participantes ativos e inativos e milestones e progresso do projeto.|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Falha na conexão com a internet** |
|1. O sistema exibe uma mensagem informando que os dados não puderam ser carregados.|
|2. O usuário pode tentar recarregar a página quando a conexão for restabelecida.|
|**A2:  Falha no carregamento de dados do GitLab** |
|1. O sistema informa que há um erro na sincronização com o GitLab.|
|2. O usuário pode tentar novamente mais tarde ou contatar o suporte técnico.|

### UC-04 - Coletar Dados via API

|UC-04 - Coletar Dados via API|           
|:---|
|**Descrição/Objetivo:** Permitir que o sistema colete dados automaticamente do GitLab por meio da API, obtendo informações relevantes sobre os projetos, como commits, issues, merge requests, milestones e estatísticas de código.|
|**Atores: Sistema**|
|**Pré-condições:** O sistema deve estar devidamente configurado com credenciais de acesso à API do GitLab e o GitLab deve estar operacional e acessível pela API.|
|**Pós-condições:** Os dados coletados são armazenados no banco de dados ou em arquivos estruturados e o dashboard é atualizado com as informações mais recentes.|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O sistema inicia a rotina de coleta de dados.|
|2. O sistema solicita e recebe os seguintes dados: Commits por usuário, Merge requests e suas aprovações, Issues abertas, fechadas e em andamento, Milestones e progresso dos projetos, Comentários e discussões, Estatísticas de código (linhas adicionadas/removidas, churn de código, etc.).|
|3. O sistema processa e estrutura os dados coletados.|
|4. Os dados são armazenados no banco de dados ou em arquivos estruturados.|
|5. O dashboard é atualizado com as informações coletadas.|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Falha na conexão com a internet** |
|1. O sistema exibe uma mensagem informando que os dados não puderam ser carregados.|
|2. O usuário pode tentar recarregar a página quando a conexão for restabelecida.|
|**A2:  Falha no carregamento de dados do GitLab** |
|1. O sistema informa que há um erro na sincronização com o GitLab.|
|2. O usuário pode tentar novamente mais tarde ou contatar o suporte técnico.|
|**A3:  Resposta incompleta da API** |
|1. O sistema recebe uma resposta parcial ou inconsistente da API.|
|2. O sistema tenta uma nova requisição.|
|3. Se a falha persistir, o sistema exibe um aviso.|

### UC-05 - Analisar Comentários e Discussões

|UC-05 - Analisar Comentários e Discussões|           
|:---|
|**Descrição/Objetivo:** Permitir que o sistema colete, analise e exiba os comentários e discussões realizadas nos projetos do GitLab, auxiliando os gestores e participantes a monitorar interações, avaliar feedbacks e acompanhar a comunicação da equipe.|
|**Atores: Gestor**|
|**Pré-condições:** O sistema deve estar devidamente configurado com credenciais de acesso à API do GitLab.|
|**Pós-condições:** Os gestores podem visualizar insights sobre a participação dos usuários nas discussões.|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O sistema inicia a coleta de dados da API do GitLab.|
|2. O sistema solicita e recebe os comentários e discussões associadas aos commits, merge requests e issues.|
|3. O gestor pode filtrar e visualizar detalhes dos comentários conforme o projeto ou participante.|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Falha na conexão com a internet** |
|1. O sistema exibe uma mensagem informando que os dados não puderam ser carregados.|
|2. O usuário pode tentar recarregar a página quando a conexão for restabelecida.|
|**A2:  Falha no carregamento de dados do GitLab** |
|1. O sistema informa que há um erro na sincronização com o GitLab.|
|2. O usuário pode tentar novamente mais tarde ou contatar o suporte técnico.|

### UC-06 - Gerenciar Informações Pessoais

|UC-06 - Gerenciar Informações Pessoais|           
|:---|
|**Descrição/Objetivo:** Permitir que os usuários visualizem e gerenciem suas informações pessoais, garantindo que os dados estejam sempre corretos.|
|**Atores: Professor**|
|**Pré-condições:** O usuário deve estar autenticado no sistema.|
|**Pós-condições:** As informações pessoais e preferências do usuário são atualizadas no sistema.|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário acessa o sistema e entra na área de perfil.|
|2. O sistema exibe as informações pessoais atuais do usuário.|
|3. O usuário altera as informações desejadas, como:
 - Notificações.
 - Tema.
 - Foto de perfil.
 - Preferências de notificação.|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Falha na conexão com a internet** |
|1. O sistema exibe uma mensagem informando que os dados não puderam ser carregados.|
|2. O usuário pode tentar recarregar a página quando a conexão for restabelecida.|
|**A2:  Falha no carregamento de dados do GitLab** |
|1. O sistema informa que há um erro na sincronização com o GitLab.|
|2. O usuário pode tentar novamente mais tarde ou contatar o suporte técnico.|
|**A3:  Falha ao salvar as preferências** |
|1. O sistema tenta salvar as alterações, mas ocorre um erro interno e exibe uma mensagem de erro.|

# Diagrama de Classes

![Diagrama de Classes](/images/Dashboard_-_Diagrama_de_Classes__ofc_.jpg)

# Diagrama de Sequências

![Diagrama de Sequencia Login](/images/Dashboard_-_Diagrama_de_Sequencia__Login_.png)

![Diagrama de Sequencia](/images/Dashboard_-_Diagrama_de_Sequencia__Login_.png)

# Diagrama de Atividades

![Diagrama de Atividades](/images/Dashboard_-_Diagrama_de_Atividades.png)

# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
