
# Metodologia

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a></span>

Para o desenvolvimento deste projeto foram adotados os fundamentos do processo ágil pautados na metodologia SCRUM.

A adoção da medologia SCRUM é a rmais condizente com a realidade do negócio e tem apoio de pesquisas acadêmicas como a da  Universidade Federal de Itajubá, realizada com uma empresa de tecnologia de pequeno porte, em que se concluiu que a aplicação deste framework apresentou: 

**"melhoria na comunicação e aumento da colaboração entre envolvidos; aumento da motivação da equipe de desenvolvimento; diminuição no tempo gasto para terminar o projeto (prazo); diminuição do risco do projeto (menor possibilidade de insucesso).*

*Outros dois benefícios presentes na literatura foram medidos e notados pelos dados quantitativos do projeto piloto e de outros projetos da empresa: diminuição dos custos de produção (mão de obra) e aumento de produtividade da equipe."*

## Relação de Ambientes de Trabalho

Os artefatos do projeto são desenvolvidos a partir de diversas plataformas e a relação dos ambientes com seu respectivo propósito deverá ser apresentada em uma tabela que especifica que detalha Ambiente, Plataforma e Link de Acesso. 
Nota: Vide documento modelo do estudo de caso "Portal de Notícias" e defina também os ambientes e frameworks que serão utilizados no desenvolvimento de aplicações móveis.

## Controle de Versão

A ferramenta de controle de versão adotada no projeto foi o
[Git](https://git-scm.com/), sendo que o [Github](https://github.com)
foi utilizado para hospedagem do repositório.

O projeto segue a seguinte convenção para o nome de branches:

- `main`: contém apenas código estável e revisado
- `dev`: usada para testar novas funcionalidades antes de serem integradas à main.
- `feature`: Para cada nova funcionalidade ou correção, cria-se uma branch a partir da dev (feature/nome-da-feature ou fix/nome-do-bug).

A árvore desse esquema ficará da seguinte forma:

main
│
└── dev
    ├── feature/sistema-login
    ├── feature/melhoria-ui
    ├── feature/ajuste-navbar
    └── ...


Quanto à gerência de issues, o projeto adota a seguinte convenção para
etiquetas:

- `documentação 📖`: relacionadas à criação ou atualização da documentação do projeto.
- `desenvolvimento 💻`: tarefas e melhorias no código relacionadas à implementação de novas funcionalidades.
- `bug 🐛`: relatórios de erros ou falhas no sistema que precisam ser corrigidos.
- `infraestrutura 🏗️`: questões ligadas à configuração do ambiente, otimização ou hospedagem.
- `teste ✅`:testes de funcionalidades, correção de erros ou criação de novos cenários de teste.

Discuta como a configuração do projeto foi feita na ferramenta de versionamento escolhida. Exponha como a gerência de tags, merges, commits e branchs é realizada. Discuta como a gerência de issues foi realizada.

> **Links Úteis**:
> - [Microfundamento: Gerência de Configuração](https://pucminas.instructure.com/courses/87878/)
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
>  - [Comparando fluxos de trabalho](https://www.atlassian.com/br/git/tutorials/comparing-workflows)
> - [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
> - [The gitflow workflow - in less than 5 mins](https://www.youtube.com/watch?v=1SXpE08hvGs)

## Gerenciamento de Projeto

### Divisão de Papéis



A equipe utiliza metodologias ágeis, tendo escolhido o Scrum como base para definição do processo de desenvolvimento. A equipe está organizada da seguinte maneira:

- **Scrum Master:** Rodrigo Taino;
- **Product Owner:** Gabriel Augusto Kuasne Grigolon;
- **Equipe de Desenvolvimento:** Rafael Rodrigues Mateus, Luiz Miguel Alves Santos e Luiz Felipe de Assis Cruz da Silva;
- **Equipe de Design:** Luiz Fernando Zacarkim Soares;

> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)
> - [Os papéis do Scrum e a verdade sobre cargos nessa técnica](https://www.atlassian.com/br/agile/scrum/roles)

### Processo

Coloque  informações sobre detalhes da implementação do Scrum seguido pelo grupo. O grupo deverá fazer uso do recurso de gerenciamento de projeto oferecido pelo GitHub, que permite acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.

Para para maximizar a transparência das informações chave, de modo que
todos tenham o mesmo entendimento dos artefatos, a equipe está utilizando o GitHub e o VS Studio Code, estruturado com as seguintes listas em modelo Kanban:

* **Fila de trabalho:** é o Backlog do Produto e lista todas as características, funções, requisitos, melhorias e correções que formam as mudanças que devem ser feitas no produto nas futuras versões;

* **Em desenvolvimento:** lista as tarefas iniciadas e ainda não concluídas para testes;

* **Em testes:** lista as tarefas aguardando a conclusão dos testes;

* **Concluído:** lista os incrementos prontos,na condição utilizável e dentro das especificações de qualidade para entrega;
 
> **Links Úteis**:
> - [Planejamento e Gestáo Ágil de Projetos](https://pucminas.instructure.com/courses/87878/pages/unidade-2-tema-2-utilizacao-de-ferramentas-para-controle-de-versoes-de-software)
> - [Sobre quadros de projeto](https://docs.github.com/pt/issues/organizing-your-work-with-project-boards/managing-project-boards/about-project-boards)
> - [Project management, made simple](https://github.com/features/project-management/)
> - [Sobre quadros de projeto](https://docs.github.com/pt/github/managing-your-work-on-github/about-project-boards)
> - [Como criar Backlogs no Github](https://www.youtube.com/watch?v=RXEy6CFu9Hk)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

### Ferramentas

As ferramentas empregadas no projeto são:

- Editor de código.
- Ferramentas de comunicação
- Ferramentas de desenho de tela (_wireframing_)

O editor de código foi escolhido porque ele possui uma integração com o sistema de versão. As ferramentas de comunicação utilizadas possuem integração semelhante e por isso foram selecionadas. Por fim, para criar diagramas utilizamos essa ferramenta por melhor captar as necessidades da nossa solução.

Liste quais ferramentas foram empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.

* Whatssapp

* Mockflow

* Microsoft Teams

* VS STUDIO CODE 
 
> **Possíveis Ferramentas que auxiliarão no gerenciamento**: 
> - [Slack](https://slack.com/)
> - [Github](https://github.com/)
