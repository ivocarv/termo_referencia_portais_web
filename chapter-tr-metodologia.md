{% include "./cabecalho.md" %}
#METODOLOGIA DE DESENVOLVIMENTO DE PORTAIS 

##Sumário

###Introdução

Este documento tem o propósito de descrever e normatizar o processo de
desenvolvimento, sustentação e testes de portais corporativos de
intranet da Polícia Federal - PF. 

A metodologia aqui descrita tem como base conceitos de Arquitetura da 
Informação e a experiência da PF no desenvolvimento e implantação de 
portais corporativos.

Existe atualmente uma estrutura básica e obrigatória definida pelas
áreas: Divisão da Comunicação Social – DCS e Coordenação-Geral de
Tecnologia da Informação – CGTI da PF. 

Essa estrutura é utilizada em todos os novos portais de intranet, 
seus procedimentos e padrões de telas encontram-se no “Manual de 
Identidade das Intranets”

Os procedimentos operacionais dos portais estão abordados no documento
“[Manual do Gestor de Conteúdo]"

É importante salientar que este documento deve ter seu uso adaptado ao
contexto de cada projeto de desenvolvimento e/ou implantação de portais.

###Conceitos

A Metodologia de Desenvolvimento de Portais - MDP é baseada nos
seguintes conceitos fundamentais: fases, papéis, atividades, artefatos e
fluxo. Em outras palavras, a metodologia possui um conjunto de papéis
(quem), interagindo com artefatos (o quê) segundo atividades
distribuídas ao longo de fases.

A MDP está dividida cronologicamente pelas seguintes fases:

-   [Planejamento do Projeto;](#_FASE_01:_Planejamento)
-   [Implantação do Portal em ambiente de desenvolvimento;](#_FASE_02:_Implantação)
-   [Identidade Visual;](#_FASE_03:_Identidade)
-   [Homologação;](#_FASE_04:_Homologação)
-   [Implantação do portal em ambiente de produção;](#_FASE_05:_Implantação)
-   [Transferência de Tecnologia.](#_FASE_05:_Transferência)

As fases podem ser executadas em ordem ou em paralelo, respeitando as
entregas e suas respectivas avaliações/aprovações.

A seguir os conceitos serão descritos de forma mais precisa.

####Fases 

Representam a dimensão tempo da metodologia de desenvolvimento. A partir
de uma perspectiva de gerenciamento, o ciclo de desenvolvimento do
portal é dividido em 06 (seis) fases sequenciais, cada uma concluída por
um marco principal, ou seja, cada fase é basicamente um intervalo de
tempo entre dois marcos principais. Um marco estabelece a condição de
passagem para próxima fase.

####Papéis 

Um papel é uma definição abstrata de um conjunto de atividades
executadas e dos respectivos artefatos. Os papéis não são pessoas, eles
descrevem como as pessoas se comportam na metodologia e quais são as
responsabilidades que elas têm.

Normalmente os papéis são desempenhados por uma pessoa ou um grupo de
pessoas que trabalham juntas em equipe. Um membro da equipe do projeto
geralmente desempenha muitos papéis distintos.

####Artefatos 

Artefatos são produtos de trabalho tangíveis e bem definidos consumidos,
produzidos ou modificados nas atividades por um ou mais papéis. Nem
todos os artefatos produzidos no projeto constam na MDP, o foco é nos
artefatos que devem ser entregues. Os templates (modelos) para os
artefatos são disponibilizados com o objetivo de orientar e facilitar a
sua elaboração. Os artefatos devem ser produzidos em formato digital de
modo a facilitar as atualizações.

####Atividades 

As atividades são grupos de tarefas sob a responsabilidade exclusiva de
um papel. Elas são distribuídas ao logo das fases de desenvolvimento,
normalmente sendo utilizadas para efeito de planejamento e controle dos
projetos. As atividades podem ser detalhadas em passos menores chamados
de tarefas.

####Fluxo 

Apresenta a sequência e a dependência entre as atividades do projeto ao
longo do tempo.

##Papéis
###Solicitante 

Representante da área usuária que detém o conhecimento, a
responsabilidade e o poder de decisão sobre as regras de negócio de um
setor da organização.

**Responsabilidades:**

-   Motivar a criação e a alteração de portais relacionados à sua área
    de negócio;
-   Definir as regras de negócio sob seu domínio;
-   Definir critérios de acesso ao portal;
-   Validar solicitações de outras áreas da PF para alterações dos
    portais sob sua responsabilidade;
-   Decidir, juntamente com o Gestor de TI, sobre mudanças de prazo,
    custo e/ou escopo que sejam identificados como crítico durante o
    processo de desenvolvimento;
-   Homologar funcionalmente os portais da sua área de negócio.

###Gestor de TI 

Responsável pela área de Tecnologia da Informação (TI) da PF que detém
conhecimento técnico e nível de decisão estratégico na Organização.

**Responsabilidades:**

-   Definir padrões tecnológicos;
-   Gerenciar recursos de TI;
-   Identificar e implantar práticas de gestão e governança de TI;
-   Renegociar prazos, custos e escopo, quando houver alterações
    relevantes;
-   Gerenciar crises.

###Gerente de Projetos 

Representante da equipe técnica que atua no planejamento, acompanhamento
e controle do projeto. Ele é o responsável pela entrega de todos os
resultados esperados do projeto.

**Responsabilidades:**

-   Alinhar e motivar os envolvidos no projeto;

-   Formar e coordenar a equipe técnica;

-   Negociar e gerenciar as expectativas dos envolvidos no projeto;

-   Facilitar a comunicação entre todos os envolvidos no projeto;

-   Planejar, acompanhar, controlar e executar os projetos em
    conformidade com a metodologia de desenvolvimento de portais;

-   Verificar se toda a documentação gerada/utilizada no projeto foi
    aprovada e armazenada no repositório do projeto;

-   Elaborar plano de projeto quando necessário;

-   Garantir que o trabalho será completado dentro do prazo, custo e
    qualidade esperados;

-   Controlar o escopo do projeto junto ao Solicitante;

-   Reportar ao Gestor de TI fatos relevantes que possam impactar no
    cronograma e nos custos.

###Analista de Portal 

Usuário designado pelo Gerente de Projetos com profundos conhecimentos
dos serviços e seus recursos, e infraestrutura de portais corporativos.

**Responsabilidades:**

-   Projetar os serviços embutidos em uma plataforma de portal;

-   Garantir aderência aos padrões tecnológicos estabelecidos;

-   Auxiliar na definição de novos padrões tecnológicos;

-   Realizar treinamento de usuários.

###Analista de Requisitos 

Membro da equipe técnica responsável por capturar as regras de negócio,
os requisitos de portal e documentos de apoio, analisá-los e
especificá-los em uma linguagem de modelagem de TI.

**Responsabilidades:**

-   Levantar e especificar requisitos e regras de negócio junto aos
    Solicitantes;

-   Especificar em linguagem de modelagem os requisitos, regras de
    negócio e workflow, se necessário;

-   Propor, definir e atualizar a documentação dos requisitos do portal;

###Desenvolvedor 

Responsável pelo desenvolvimento de páginas web, portlets, integrações e
implantações de serviços embutidos à plataforma de portal, de acordo com
as especificações recebidas.

**Responsabilidades:**

-   Auxiliar na elaboração do projeto detalhado do portal;

-   Desenvolver os produtos e componentes de portais solicitados de
    acordo com as especificações e prazos estabelecidos;

-   Elaborar documentação dos produtos entregues;

-   Implementação de Temas.

###Web designer 

Membro da equipe técnica que elabora design da interface com o
Solicitante. Isso inclui reunir os requisitos de utilidade e desenvolver
os protótipos para atender a esses requisitos.

**Responsabilidades:**

-   Desenvolver protótipos navegáveis e reutilizáveis das interfaces;

-   Projetar interfaces gráficas;

-   Implementar e criar, quando solicitado, padrões visuais, tais como,
    logomarcas, banners e imagens.

###Analista de Testes 

Técnico responsável por planejar e executar os testes nos portais.

**Responsabilidades:**

-   Planejar testes.

-   Executar e documentar testes.

##Artefatos

O quadro a seguir mostra a lista de artefatos que serão produzidos no decorrer das fases, e a localização dos seus templates.

  **LISTA DE ARTEFATOS**               **DESCRIÇÃO**            **NOME DOS TEMPLATES**
  Ordem de Serviço/ *Checklist*        Descreve uma visão geral do projeto descrita pelo Solicitante, suas necessidades, requisitos iniciais e suas características. O Checklist encontra-se no [Anexo I](#_ANEXO_I) a este documento.   TP - Sigla Projeto –Checklist
  Lista de Requisitos                  Permite uma visualização sintética dos requisitos que o portal deverá atender.                                                                                                                    TP - Sigla Projeto - Lista de Requisitos
  Ata de reunião                       Registro das ações tomadas nas reuniões e aprovação dos participantes                                                                                                                             TP - Sigla do Projeto - Ata de Reunião
  Termo de Aceite                      Documento usado para a homologação dos produtos entregues                                                                                                                                         TP - Sigla Projeto - Termo de Aceite
  Resultado de Testes                  Relatar o resultado dos testes aplicados.                                                                                                                                                         TP - Sigla Projeto – Resultado de Teste
  Manual do Gestor de Conteúdo         Aborda os procedimentos operacionais dos portais intranets.                                                                                                                                       GO - Sigla Projeto – Manual do Gestor de Conteúdo
  Manual de Identidade das Intranets   Documento que define a identidade visual base para os portais de intranet.                                                                                                                        GO - Sigla Projeto – Manual de Identidade das Intranets
##FASES DO DESENVOLVIMENTO 

Nas seções seguintes, as fases e respectivas atividades serão
detalhadas. As fases são compostas por um conjunto de atividades, cada
uma delas sob responsabilidade de um papel que interage com um conjunto
de artefatos de entrada produzindo artefatos de saída. As atividades
podem ser divididas em passos menores chamados de tarefas.

###Planejamento do Projeto 

A principal meta da fase de Planejamento do Projeto é atingir um
consenso entre todos os envolvidos sobre o produto/serviço que deverá
ser entregue, e validar as informações preenchidas no *Checklist*,
enviado na Ordem de Serviço.

#### Atividade: Abertura do Projeto 

  **Objetivos**       -   Formar a equipe técnica do projeto, definir os papéis entre os membros da equipe técnica, criar o repositório do projeto e fazer a reunião de abertura com o Solicitante.
                      
  **Responsável**     -   Gerente de Projetos

  **Participantes**   -   Gestor de TI
                      -   Solicitante
                      -   Gerente de Projetos
                      -   Analista de Portal
                      -   Analista de Requisitos
                      -   Analista de Testes
                      -   Implementador
                      -   Web Designer

  **Tarefas**         -   Formar equipe técnica
                      -   Realizar reunião com a equipe técnica para definição dos papéis
                      -   Criar repositório no SVN para o projeto
                      -   Realizar reunião com o Solicitante.
                      -   Determinar prazo para o projeto
                      

  **Templates**       -   [Ata de Reunião](#_Artefatos)
                      -   [Checklist](#_Toc350577509)

  **Ferramentas**     -   Editor de texto
                      -   SVN – sistema para controle de versões

  **Entradas**        -   Ordem de Serviço

  **Saídas**          -   Repositório do projeto no SVN
                      -   Ata da reunião

  **Observações**     O Projeto só estará formalmente iniciado se o *Checklist* estiver devidamente respondido e validado pela equipe de desenvolvimento de portal.

#### Atividade: Detalhamento dos Requisitos 
  **Objetivos**       -   Detalhar os requisitos funcionais, de conteúdo, permissões e de layout, para definir a arquitetura das informações dentro dos padrões de identidade visual preestabelecidos.
                      
  **Responsável**     -   Analista de Requisitos

  **Participantes**   -   Gerente de Projetos
                      -   Analista de Portal
                      -   Web Design

  **Tarefas**         -   Coletar e detalhar os requisitos funcionais
                      -   Coletar e detalhar os requisitos de conteúdo
                      -   Coletar e detalhar os requisitos de layout
                      -   Coletar e detalhar requisitos de permissões

  **Templates**       -   [Lista de Requisitos](#_Toc350577509)
                      
  **Ferramentas**     -   Editor de texto
                      -   SVN– sistema para controle de versões

  **Entradas**        -   Ordem de Serviço

  **Saídas**          -   Lista de Requisitos

  **Observações**     A Lista de Requisitos deve ser aprovada formalmente pelo Solicitante.

#### Validação da OS e dos Requisitos do Projeto 

A fase terá chegado ao fim e atingido seus objetivos quando a OS estiver
validada, a Ata de Reunião estiver publicada, e a Lista de Requisitos
estiver aprovada formalmente pelo Solicitante. O marco da fase de
iniciação permite avaliar se as necessidades do Solicitante serão
atendidas com os padrões já existentes. Impasses devem ser resolvidos
pelo Gestor de TI.

###Implantação do Portal em ambiente de desenvolvimento 

O objetivo principal da fase de Implantação do Portal em ambiente de
desenvolvimento é realizar a pré-configuração do SGC, processo de
criação de um ambiente de desenvolvimento e adição do portal modelo. A
fase é concluída com a validação da estrutura em ambiente de
desenvolvimento.

#### Criação do ambiente de desenvolvimento. 

  **Objetivos**       -   Criação do portal em ambiente de desenvolvimento.
  **Responsável**     -   Desenvolvedor
  **Participantes**   -   Analista de Portal
  **Tarefas**         -   Importar o Portal Modelo
                      -   Criar Script de Hierarquia
                      -   Criar plugins
                      -   Adaptar plugins
                      -   Resolver, caso necessário, problemas relacionados à infraestrutura
                      -   Validar componentes criados

  **Templates**       -   [Manual de Identidade das Intranets](#_Toc350577509)
                      
  **Ferramentas**     -   SGC
                      -   Editor de texto
                      -   Editor de código
                      -   Aplicativo de Modelagem UML

  **Entradas**        -   Ordem de Serviço
                      -   Lista de requisitos

  **Saídas**          -   Script de Hierarquia
                      -   Portal em ambiente de desenvolvimento e pré-ajustado

  **Observações**     


####Atividade: Permissões 

  **Objetivos**       -   Conectar com a base de usuários LDAP para autenticação de usuários, e criar grupos e permissões conforme levantamento de requisitos.
  **Responsável**     -   Desenvolvedor
  **Participantes**   -   Analista de Portal
  **Tarefas**         -   Integrar autenticação via LDAP
                      -   Criar usuários
                      -   Criar grupos
                      -   Aplicar permissões

  **Templates**       -   [Lista de Permissões](#_Toc350577509)
  **Ferramentas**     -   SGC
                      -   Conector LDAP

  **Entradas**        -   Portal em ambiente de desenvolvimento e pré-ajustado

  **Saídas**          -   Portal conectado com o LDAP e permissões ajustadas
                      -   Lista de Permissões
                      
  **Observações**     A equipe de Suporte poderá ser acionada sempre que necessário. Reportar ao Solicitante a criação do Portal em ambiente de desenvolvimento com as permissões requisitadas.

#### Implementação dos Requisitos de Identidade Visual 
  **Objetivos**       -   Desenvolver ou adaptar Temas
  **Responsável**     -   Web Designer
  **Participantes**   -   Analista de Portal
                      -   Desenvolvedor
  **Tarefas**         -   Criar protótipo de layout
                      -   Criar *portlets*
                      -   Criar demais elementos visuais
                      -   Criar produto de Tema

  **Templates**       -   [Manual de Identidade das Intranets](#_Toc350577509)

  **Ferramentas**     -   Editor de texto
                      -   Editor visual
                      -   Editor de código
                      -   SGC

  **Entradas**        -   Portal em ambiente de desenvolvimento e pré-ajustado

  **Saídas**          -   Protótipo do portal
                      -   Portal nos padrões de identidade visual
                      
  **Observações**     
                      
#### Versão do Portal para Testes 

O fim desta fase é ocorre com a entrega do portal em ambiente de
desenvolvimento com todos os requisitos aplicados para aceitação do
Solicitante.

###Homologação 

Nesta fase o produto final deve ser testado pelo Solicitante e migrado
para ambiente de homologação.

####Atividade: Teste 
  **Objetivos**       -   Acesso ao portal em ambiente de desenvolvimento para realizar os testes finais.
  **Responsável**     -   Gerente de Projetos
  **Participantes**   -   Solicitante
                      -   Analista de Portal
                      -   Analista de Testes

  **Tarefas**         -   Registrar os ajustes, caso necessário.
                      -   Implantar ajustes
                      -   Coletar assinatura do termo de aceite

  **Templates**       -   [Termo de Aceite](#_Toc350577509)
                      -   [Resultado de Teste](#_Toc350577509)

  **Ferramentas**     

  **Entradas**        -   Portal em homologação

  **Saídas**          -   Termo de Aceite ou Resultado de Testes
                      -   Versão do portal para produção

  **Observações**     Em casos de detecção de erros durante a homologação que não permitam a subida do portal para o ambiente de produção, a saída desta atividade é o documento “Resultado de Testes”, e a atividade Testar é realizada novamente. Se a homologação ocorrer com sucesso, o documento a ser gerado é o “Termo de Aceite”.

####Migração para o ambiente de homologação 
      **Objetivos**       -   Migração do portal para ambiente de homologação a fim de executar testes, e obter a versão final do produto com o acordo do Solicitante.
      **Responsável**     -   Analista de Portal
      **Participantes**   -   Desenvolvedor
      **Tarefas**         -   Auxiliar as equipes de Suporte na tarefa de copiar o portal do ambiente de desenvolvimento para o ambiente de homologação
                          -   Testar ambiente de homologação
      **Templates**       
      **Ferramentas**     -   SGC
      **Entradas**        -   Versão do Portal para Testes
      **Saídas**          -   Portal em homologação
      **Observações**     As equipes de Suporte devem ser envolvidas nessa atividade.

####Portal em homologação 

O fim desta fase é ocorre com a entrega do portal em ambiente de
homologação, testado, e com todos os requisitos aplicados para aceitação
do Solicitante.

###Implantação do portal em ambiente de produção 
    
Nesta fase o produto final é estabelecido em ambiente de homologação.
####Migração para o ambiente de produção 

  **Objetivos**       -   Copiar o portal testado e homologado para o ambiente de produção

  **Responsável**     -   Analista de Portal
  **Participantes**   -   Desenvolvedor
  **Tarefas**         -   Auxiliar as equipes de Suporte na tarefa de copiar o portal do ambiente de homologação para o ambiente de produção
                      -   Testar ambiente de produção
  **Templates**       
  **Ferramentas**     -   SGC
  **Entradas**        -   Versão do portal para produção
  **Saídas**          -   Produto Final
  **Observações**     

####Produto Final 

A fase de transição chega ao fim com a aprovação do produto final pelo
Solicitante.

###Transferência de Tecnologia 

Na Transferência de Tecnologia ocorre um único treinamento, baseado no
Manual do Gestor de Conteúdo, que capacita o usuário para utilizar as
funcionalidades portal; também tira dúvidas sobre atividades
relacionadas à gestão do portal que o Solicitante achar pertinente.

Esse treinamento pode acontecer de forma remota ou presencial.
Realizar-se-á uma única vez dentro do projeto específico, porém o
Solicitante pode requerer novos treinamentos durante a sustentação do
portal, que é realizada posteriormente á entrega do produto.

####Treinar Usuários 

      **Objetivos**       -   Treinar usuários nas funcionalidades do portal da unidade.
      **Responsável**     -   Analista de Portal
      **Participantes**   -   Gerente de Projetos
                          -   Solicitante
                          -   Usuários
      **Tarefas**         -   Agendar treinamento
                          -   Executar treinamento
      **Templates**       
      **Ferramentas**    
      **Entradas**        -   Manual do Gestor de Conteúdo
      **Saídas**          -   Treinamento para o uso adequado do portal intranet
                          -   Lista de Presença
      **Observações**     Usuário é a pessoa ou grupo de pessoas indicadas pelo Solicitante para serem os multiplicadores.

####Equipe capacitada para uso do portal corporativo 
A fase de transferência de conhecimento habilita o usuário para o uso do
portal e define o fim do projeto.

