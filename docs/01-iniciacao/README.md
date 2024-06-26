# Iniciação

>A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
>Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
>É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
>Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
>Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
>O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Critérios de Sucessos](#critérios-de-sucesso)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos Preliminares](#requisitos-preliminares)
- [Partes Interessadas](#partes-interessadas)
- [Estimativa de Custo e Prazo](#estimativa-de-custo-e-prazo)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
- [Documentos](#documentos)
  - [Declaração de Escopo](#declaração-de-escopo)
  - [Registro de Partes Interessadas](#registro-de-partes-interessadas)
  - [Termo de Abertura do Projeto (TAP)](#termo-de-abertura-do-projeto-tap)

# Introdução

## Problema

O transtorno do espectro autista (TEA) é um distúrbio do neurodesenvolvimento caracterizado por desenvolvimento atípico, manifestações comportamentais, déficits na comunicação e na interação social, padrões de comportamentos repetitivos e estereotipados, podendo apresentar um repertório restrito de interesses e atividades. Tendo isso em vista, o TEA compromete a independência e qualidade de vida dos indivíduos. 

<!-- > Problem corresponde a uma lacuna a ser preenchida, uma necessidade a ser atendida, ou uma dificuldade a ser superada.
> A definição precisa do problema ajuda a orientar as atividades do projeto, direcionando os esforços em sua solução.
> Seu entendimento facilita a comunicação eficaz entre os membros da equipe e as partes interessadas, estabelecendo uma base comum para a colaboração.
> Nesta seção, deve ser descrito apenas o problema e seu contexto.
> Soluções para o problema devem ser descritas na seção correspondente. -->

## Objetivos

### Objetivo Geral

Ajudar pessoas com Transtorno do Espectro Autista a serem mais independentes e autônomas. 

### Objetivo Específico

 1. Computar e analisar crises
 2. Acompanhar tarefas rotineiras
 3. Disponibilizar opções para relaxamento
 4. Monitorar crises

<!-- > Aqui você deve descrever os objetivos do trabalho.
> Apresente um Objetivo Geral, sintetizado em uma única frase.
> Apresente também 3 ou 4 objetivos específicos (sub-produtos do sistema ou objetivos extras que podem ser alcançados pela construção do software).
> 
> **Link Útil**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/) -->

 
# Especificações do Projeto

Para que o Spectro Buddy seja possível será necessário utilizar as seguintes técnicas e ferramentas:

1. **Agenda Inteligente**: Implementação de uma agenda para monitorar as tarefas rotineiras.
2. **Pictograma**: Utilização de emoji e pictogramas para possibilitar a comunicação não verbal do indivíduo.
3. **Gráficos**: Utilização de gráficos para um melhor monitoramento e análise de crises de uma pessoa com TEA.
4. **Alertas e Notificações**: Implementação de alertas e notificações de tarefas rotineiras, evitando que a pessoa com TEA as esqueça.
5. **Lista de contatos**: Implementação de uma lista de contatos para monitoramento do ciclo social da pessoa com TEA, auxiliando no seu filtro social.
6. **Plataforma de Aplicativos**: Desenvolvimento de aplicativos que conectam e comunicam entre si, utilizando o conceito de IOT, para fornecer o suporte que a pessoa com TEA precisa.

<!-- > Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar as especificações do projeto. -->

## Critérios de Sucesso

<!-- > Os critérios de sucesso de um projeto fornecem uma estrutura clara para avaliar o êxito do trabalho e analisar se o projeto realmente alcançou os objetivos estabelecidos. 
> Esses critérios geralmente abrangem diversas dimensões, incluindo a entrega dentro do prazo e orçamento estipulados, a satisfação do cliente, a qualidade do produto ou serviço final, e a eficiência na utilização de recursos. 
> Além disso, a capacidade de atender aos requisitos e expectativas das partes interessadas, bem como a gestão eficaz de riscos, são considerados aspectos importantes para determinar o sucesso de um projeto. -->

1. **Número de download** - Após um tempo do lançamento dos apps nas lojas de aplicativos, o número de download de todos os aplicativos somados deve ser superior a 200;
2. **Acessibilidade** - Os aplicativos produzidos devem ser acessíveis a pessoas com TEA;
3. **Conectividade** - Não haver problemas com a conexão entre apps;
4. **Avaliações de pessoas com TEA** - avaliação positiva de pessoas com TEA;
5. **Aprovação Profissional** - avaliação e aprovação de profissionais que atuam na área de saúde, como psicólogos, psiquiatras e neurologista;
6. **Entrega dentro do orçamento e prazo** - o projeto deve obedecer a prazos e a orçamentos estipulados.
 
## Histórias de Usuários

<!-- ......  ATUALIZE AS HISTÓRIAS DE USUÁRIOS ABAIXO (MÍNIMO 20) ...... -->

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO...                     | QUERO/PRECISO ...                               |PARA ...                                                          |
|-------------------------------|-------------------------------------------------|------------------------------------------------------------------|
|Cuidador de uma pessoa com TEA | Registrar tarefas da pessoa com TEA             | A pessoa com TEA não esquecer de fazê-las                        |
|Cuidador de uma pessoa com TEA | Controlar remédios e crises                     | Ter noção do estado da pessoa com TEA                            |
|Cuidador de uma pessoa com TEA | Acessar informações importantes no smartwatch   | A pessoa com TEA tenha suporte mais rápido                       |
|Pessoa com TEA                 | Registrar minhas tarefas                        | Não esquecer de fazê-las                                         |
|Pessoa com TEA                 | Notificar tarefas                               | Ter o suporte que precisa                                        |
|Pessoa com TEA                 | Ter alertas de tarefas                          | Ter o suporte que precisa                                        |
|Pessoa com TEA                 | Controlar remédios e crises                     | Ter o suporte que precisa                                        |
|Pessoa com TEA                 | Acessar informações importantes no smartwatch   | Possa ter o suporte que precisa rapidamente                      |
|Pessoa com TEA                 | Acessar funcionalidades para tranquilizar       | Ajudar durante alguma crise                                      |
|Pessoa com TEA                 | Possua emoji no aplicativo                      | Realizar linguagem não verbal                                    |
|Pessoa com TEA não verbal      | Possua pictogramas no aplicativo                | Conseguir entender o aplicativo                                  |
|Administrador                  | Alterar permissões                              | Permitir que possam administrar contas                           |
|Administrador de Redes         | Acessar banco de dados e back-end               | Permitir a conexão de aplicativos entre si e com banco de dados  |
|DBA                            | Acessar ao banco de dados                       | Desenvolver banco de dados                                       |
|Design de interfaces           | Acessar a ferramentas de design                 | Desenlvover projetos de interfaces acessíveis                    |
|Desenvolvedor                  | Acessar a ferramentas de desenvolvimento mobile | Desenvolver aplicativos                                          |
|Desenvolvedor                  | Acessar a documentações de código               | Auxiliar no desenvolvimento do código                            |
|Desenvolvedor                  | Acessar projeto de interfaces                   | Desenvolver aplicativos                                          |
|Médico                         | Visualizar dados e estatísticas sobre crises    | Saber como se deve prosseguir no tratamento da pessoa com TEA    |
|Gerente de projeto             | Acessar códigos produzidos                      | Acompanhar e orientar as tarefas do projeto                      |
|Analista de Sistemas           | Acessar dados gerados no sistema                | Produzir relatórios                                              |

<!-- > As Histórias de Usuário consistem em uma ferramenta importante para a compreensão e elicitação dos requisitos.
> Defina atores (ou personas), se for o caso, um administrador para criação das histõrias de usuário.
> As histórias de usuário posteriormente devem ser utilizadas para preenchimento dos Requisitos Funcionais.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac) -->

## Requisitos Preliminares

<!-- > Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas.  -->

<!-- > Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/) -->

### Requisitos Funcionais

<!-- ......  ATUALIZE OS REQUISITOS FUNCIONAIS DO SISTEMA (MÍNIMO 20) ...... -->

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito                                                                   | Prioridade |
|------|------------------------------------------------------------------------------------------|-------|
|RF-001| Permitir que o usuário cadastre tarefas                                                  | ALTA  | 
|RF-002| Emitir um relatório de tarefas no mês                                                    | MÉDIA |
|RF-003| Permitir que o usuário registre crises                                                   | ALTA  |
|RF-004| Permitir que o usuário realize exercício de respiração                                   | MÉDIA |
|RF-005| Permitir que o usuário visualize gráfico gerados com dados de crises                     | BAIXA |
|RF-006| Permitir que o usuário edite crises registradas                                          | ALTA  |
|RF-007| Permitir que o usuário delete crises                                                     | ALTA  |
|RF-008| Permitir que o usuário edite tarefas                                                     | ALTA  |
|RF-009| Permitir que o usuário exclua tarefas                                                    | ALTA  |
|RF-010| Permitir que o usuário visualize as tarefas                                              | ALTA  |
|RF-011| Permitir que o usuário do Spectro Laranja personalize as funcionalidades do Spectro Roxo | ALTA  |
|RF-012| Permitir que o usuário do Spectro Azul se conecte ao Spectro Verde                       | ALTA  |
|RF-013| Permitir que o usuário do Spectro Laranja se conecte ao Spectro Verde                    | ALTA  |
|RF-014| Permitir que o usuário do Spectro Azul personalize funcionalidades do Spectro Verde      | MÉDIA |
|RF-015| Permitir que o usuário do Spectro Laranja personalize funcionalidades do Spectro Verde   | MÉDIA |
|RF-016| Permitir que o usuário do Spectro Verde cadastre crises                                  | MÉDIA |
|RF-017| Permitir que o usuário do Spectro Verde visualize tarefas                                | MÉDIA |
|RF-018| Permitir que o usuário do Spectro Verde realize exercícios de respiração                 | BAIXA |
|RF-019| Permitir que o usuário do Spectro Verde utilize linguagem não verbal                     | ALTA  |
|RF-020| Permitir que o usuário do Spectro Roxo utilize linguagem não verbal                      | ALTA  |


### Requisitos Não Funcionais

<!-- ......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ...... -->

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                                          |Prioridade |
|-------|---------------------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ser responsivo para rodar em dispositivos móveis                 | MÉDIA     | 
|RNF-002| Os aplicativos para celulares devem ser compatíveis com Android e IOS           | ALTA      |
|RNF-003| O Spectro Laranja deve se conectar com o Spectro Roxo através do banco de dados | ALTA      |
|RNF-004| O Spectro Laranja deve se conectar com o Spectro Verde por bluetooth            | ALTA      |
|RNF-005| O Spectro Azul deve se conectar com o Spectro Verde por bluetooth               | ALTA      |
|RNF-006| O Spectro Azul deve enviar notificações                                         | ALTA      |
|RNF-007| O Spectro Azul deve enviar alertas                                              | ALTA      |
|RNF-008| O Spectro Roxo deve enviar notificações                                         | ALTA      |
|RNF-009| O Spectro Roxo deve enviar alertas                                              | ALTA      |

### Restrições

<!-- ......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ...... -->

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição da Restrição                                                         | Prioridade |
|------|--------------------------------------------------------------------------------|------------|
|RE-001| Compatibilidade do aplicativo com diversos dispositivos disponíveis no mercado | ALTA       | 
|RE-002| Desing das interfaces deve ser acessível a pessoas com TEA                     | MÉDIA      |
|RE-003| Recursos disponibilizados em frameworks e linguagens de programação            | BAIXA      |
|RE-004| Recursos Financeiros Limitados                                                 | MÉDIA      |
|RE-005| Limitações na utilização ou conexão com API ou software de terceiros           | ALTA       |

# Partes Interessadas

<!-- > Relacione as partes interessadas no seu projeto.  -->
<!-- > Você deve descrever as partes interessadas e indicar qual o nível de influência em relação ao projeto. -->
<!-- > Indique as principais pessoas (clientes, fornecedores, etc), indicando possíveis expectativas, nível de influência e possível importância para o sucesso do projeto. -->

| Nome                                  | Expectativas no projeto              | Influência |	Importância / Poder	| Apoio    |
|---------------------------------------|--------------------------------------|------------|---------------------|----------|
| Gabriel Luís                          |	Desing                               | Baixa      | Baixa               | Apoiador |
| Leornado Piuzana                      |	Desenvolvedor                        | Baixa      | Baixa               | Apoiador |
| Paula Talim	                          | Gerenciar projeto                    | Média      | Média               | Apoiador |
| Rafael Vicente                        |	Gerenciar banco de dados	           | Baixa      | Baixa               | Apoiador |
| Profissionais da área de saúde mental |	Promover o projeto	                 | Alta	      | Média               | Apoiador |
| Usuários com TEA e seus cuidadores    |	Opinião pública                      | Alta	      | Alta	              | Neutro   |
| Lojas de aplicativo	                  | Acessibilidade do público ao projeto | Alta	      | Alta                | Apoiador |


# Estimativa de Custo e Prazo

## Estimativa de Custo

<!-- > A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados. -->

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        | Funcionário do setor financeiro | 800 | R$ 28,00 |   22400,00 |
| Hardware                | Smartwatch | 0          | R$ 0,00      | R$ 0,00     |
| Serviços de Rede        |      -     | 0          | R$ 0,00      | R$ 0,00     |
| Hospedagem e Nuvem      | Github     | 2000       | R$ 0,00      | R$ 0,00     |
| Software de terceiros   | Banco de dados, ícones e pictogramas | 2000          | R$ 0,00      | R$ 0,00     |
| Serviços e treinamento  |            | 2000       | R$ 100,00    | R$ 200000,00|
| **Total Geral**         |            | 6880       | R$ 128,21    | R$ 223000,00|


## Estimativa de Prazo

<!-- > A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis. -->

 - Prazo previsto (em horas) : 320 horas
 - Data de início : 12/04/2024 08:00
 - Data de término : 28/05/2024 08:00

# Metodologia

<!-- > Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0) -->

Para que o Spectro Buddy seja possível de se desenvolver foi adotada um framework Scrum, como uma metologia ágil para organizar as demandas e executar as tarefas, permitindo uma entrega rápida e de alta qualidade do produto. A seguir está alguns detalhes desse processo.

## Ciclo de Trabalho

**1. Planejamento**

Estabelecer as bases  do projeto, identificando os objetivos, requisitos e restrições, além de planejar as atividades necessárias para a sua execução.

**2. Análise de Requisitos**

Coletar e analisar os requisitos funcionais e não funcionais do aplicativo,  incluindo  as  necessidades  específicas  dos  usuários  autistas  e  as  funcionalidades necessárias para atendê-las. 

**3. Design**

Criar o design detalhado do aplicativo, incluindo a interface do usuário, arquitetura de software, fluxo de navegação e experiência  do usuário,  garantindo que atenda  aos  requisitos identificados na fase anterior. 

**4. Desenvolvimento**

Desenvolvimento de 4 aplicativos, sendo eles:

- **Spectro Roxo**: Aplicativo voltado para autistas níveis 2 ou 3, nesse app terá pictogramas, notificações sobre as tarefas que o usuário precisa fazer e funcionalidades para relaxar, como a opção de colocar música. 

- **Spectro Laranja**: Aplicativo voltado aos cuidadores de autista nível 2 ou 3, nele é possível controlar remédios, crises e rotina da pessoa com o transtorno, assim, será possível configurar notificações que aparecerá app para autista nível 2 e 3. Além de conseguir controlar os sinais vitais do autista, através do app para smartwatch. 

- **Spectro Azul**: Aplicativo voltado para autista nível 1, nele haverá a possibilidade de controle de remédios, sinais vitais, crises e rotina, além de funcionalidades para relaxar, como a opção de colocar músicas. Assim, o app terá alertas configurados pelo próprio usuário e terá a possibilidade de se conectar com o app para smartwatch. 

- **Spectro Verde**: Aplicativo voltado para smartwatch para pessoas autistas, esse app irá ler os dados dos sinais vitais do usuário, podendo enviá-los para os aplicativos para cuidadores ou para autistas de nível 1. Além disso, o aplicativo irá mostrar as notificações configurações nos app conectados.

**5. Testes**

Realizar  testes  rigorosos  para  garantir  a  qualidade  e  a  usabilidade  do  aplicativo, incluindo  testes  funcionais,  de  usabilidade  e  de  acessibilidade,  identificando  e  corrigindo quaisquer defeitos ou problemas encontrados. 

**6. Implantação**
 
Preparar  o  aplicativo  para  o  lançamento  público,  incluindo  a  configuração  de ambientes  de  produção,  migração  de  dados,  treinamento  de  usuários  e  implementação  de estratégias de lançamento e marketing. 

**7. Manutenção e Suporte**

Fornecer suporte contínuo ao aplicativo após o lançamento, incluindo a correção de bugs, atualizações de segurança, melhorias de desempenho e lançamento de novas versões com base no feedback dos usuários.

## Divisão de Papéis

| Membro         | Papel                       |
|----------------|-----------------------------|
| Lornado Pizani | Gerência de Desenvolvimento |
| Gabriel Luís   | Gerência do Front-end       |
| Paula Talim    | Gerência de Tarefas         |
| Rafael Vicente | Gerência do Banco de Dados  |

## Ferramentas

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/orgs/ICEI-PUC-Minas-PMG-EC-GPS/projects/7/views/1 | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/ICEI-PUC-Minas-PMG-EC-GPS/pmg-ec-2024-01-gps-92470101-time-grp2 | Hospedagem |
| Protótipo Interativo  | Figma              | https://www.figma.com/design/NRsvA6N286mr4Tv7cBRT9A/SpectroBuddy?node-id=0-1&t=tJBuoRsJfIWzUv5e-1  | |
| Documentos Textuais   | LibreOffice Writer | N/A                        |              |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |              |
| EAP / WBS             | Miro               | https://miro.com/app/board/uXjVNgV2U68=/?share_link_id=486322437169 | |
| Cronograma do Projeto | ProjectLibre       | https://www.projectlibre.com |            |
| Matriz RACI           | Microsoft Word     | https://www.microsoft.com/pt-br/microsoft-365/word | |

# Documentos

## Declaração de Escopo

- [Declaração de Escopo](artefatos/declaracao-escopo.pdf)

## Registro de Partes Interessadas

- [Registro de Partes Interessadas](artefatos/registro-partes-interessadas.xlsx)

## Termo de Abertura do Projeto (TAP)

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

- [Termo de Abertura do Projeto](./artefatos/Termo%20de%20Abertura%20de%20Projeto.pdf)
