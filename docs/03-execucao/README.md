# Execução

> A fase de execução na gerência de projetos é o momento em que as atividades planejadas são realizadas. 
> Durante essa etapa, os membros da equipe executam suas tarefas de acordo com o cronograma estabelecido, os recursos são alocados conforme as necessidades e as comunicações são fundamentais para garantir que todos estejam alinhados com os objetivos. 
> O gerente de projeto atua na coordenação das atividades, resolução de problemas e na gestão de mudanças inesperadas. 
> Além disso, o monitoramento constante é essencial para garantir que o projeto esteja avançando conforme o planejado, e ajustes são feitos conforme necessário. 
> A fase de execução é o momento em que o trabalho tangível é realizado, e a eficácia nessa etapa contribui diretamente para o sucesso geral do projeto.

# Estrutura do Documento

- [Fase de Execução](#execução)
- [Interfaces do Sistema](#interfaces-do-sistema)
- [Modelagem da Solução](#modelagem-da-solução)
  - [Arquitetura da Solução](#arquitetura-da-solução)
  - [Diagrama de Classes](#diagrama-de-classes)
  - [Persistência dos Dados](#persistência-dos-dados)


# Interfaces do Sistema

 Os protótipos navegáveis oferecem uma representação interativa das interfaces e funcionalidades do sistema antes da implementação final. 
 Esses protótipos permitem que os usuários experimentem a navegação real entre telas e interajam com elementos de interface, proporcionando uma visão prática do design proposto. 
 Ao criar protótipos navegáveis, os desenvolvedores podem validar conceitos, testar a usabilidade e obter feedback de stakeholders e usuários finais. 
 Essa abordagem contribui para a detecção precoce de possíveis problemas de usabilidade, refinando o design e economizando tempo e recursos durante o ciclo de desenvolvimento. Sendo assim, a seguir está os Diagramas de Fluxo do Usuário desenvolvidos para cada aplicativo do projeto.

> **Observação**: Clique nos *Diagramas de Fluxo do Usuário* a seguir para acessar seu protótipo navegável.

## Spectro Verde - *Aplicativo para Smartwatch*

[![fluxograma app smartwatch](./images/interfaces_spectroVerde.png)](https://www.figma.com/proto/NRsvA6N286mr4Tv7cBRT9A/SpectroBuddy?node-id=211-173&t=P0AIL9t6NrjiREgO-1&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=211%3A173&show-proto-sidebar=1)

## Spectro Azul - *Aplicativo para pessoas com TEA nível 1*

[![fluxograma app SpectroAzul](./images/interfaces_spectroAzul.png)](https://www.figma.com/proto/NRsvA6N286mr4Tv7cBRT9A/SpectroBuddy?node-id=204-69&t=P0AIL9t6NrjiREgO-1&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=204%3A69&show-proto-sidebar=1)

## Spectro Laranja - *Aplicativo para cuidadores de pessoas com TEA nível 2 ou 3*

[![fluxograma app SpectroLaranja](./images/interfaces_spectroLaranja.png)](https://www.figma.com/proto/NRsvA6N286mr4Tv7cBRT9A/SpectroBuddy?node-id=356-15&t=iikM5kugf4JOiFR2-1&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=356%3A15&show-proto-sidebar=1)

## Spectro Roxo - *Aplicativo para pessoas com TEA nível 2 ou 3*

[![fluxograma app SpectroRoxo](./images/interfaces_spectroRoxo.png)](https://www.figma.com/proto/NRsvA6N286mr4Tv7cBRT9A/SpectroBuddy?node-id=362-2&t=iikM5kugf4JOiFR2-1&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=362%3A2&show-proto-sidebar=1)

# Modelagem da Solução

> A modelagem de software envolve a criação de representações abstratas que capturam a estrutura, comportamento e interações do software a ser desenvolvido. 
> Esses modelos servem como guias visuais que auxiliam na compreensão e comunicação entre os membros da equipe de desenvolvimento. 
> A modelagem de software abrange diversas técnicas, como diagramas de classes, diagramas de sequência e diagramas de caso de uso, proporcionando uma representação visual clara das relações e funcionalidades do sistema. 
> Essa abordagem facilita a identificação precoce de requisitos e a detecção de inconsistências. 
> Além disso, a modelagem contribui para a documentação eficaz, permitindo uma compreensão mais abrangente do software antes mesmo de sua implementação. 

## Arquitetura da solução

 A arquitetura de software define a organização de um sistema, definindo seus componentes e suas relações.
 Abrange escolhas de design que influenciam aspectos como desempenho, escalabilidade, segurança e manutenibilidade do software. 
 A arquitetura de software serve como um mapa que orienta as decisões de desenvolvimento, fornecendo uma visão global que facilita a compreensão e a colaboração entre membros da equipe. 
 Uma arquitetura bem projetada promove a modularidade, facilitando a evolução e a manutenção do sistema ao longo do tempo.

Para a arquitetura do sistema foi optado pela abordagem monolítica, pois, apesar das diferenças entre aplicativos, os dados persistentes não serão tão diferentes ao ponto de ser necessário uma divisão do banco de dados.

![Arquitetura SpectroBuddy](images/arquitetura-sistema.png)


<!-- ## Diagrama de Classes

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE CLASSES .......

> O diagrama de classes fornece uma representação visual das estruturas e relações entre as classes em um sistema orientado a objetos. 
> O diagrama serve como uma documentação visual eficaz, facilitando a compreensão, manutenção e contínua do software.
>
> **Diagrama de Classes:**
> Desenvolva um diagrama de classes para o sistema proposto.
> Caso a solução fique muito grande, divida o diagrama por módulos ou serviços.
> Explique de forma concisa o diagrama, para que seja possível entender a solução proposta.
>
> **Exemplo de diagrama de Classes**:
> ![Exemplo de diagrama de Classes](images/class-diagram.png) -->


## Persistência dos Dados

![Diagrama de Banco de Dados](images/projeto_database.png)


