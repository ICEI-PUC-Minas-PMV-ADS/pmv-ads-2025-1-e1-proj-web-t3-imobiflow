
# Metodologia

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a></span>

Para o desenvolvimento deste projeto foram adotados os fundamentos do processo ágil pautados na metodologia SCRUM.

A adoção da medologia SCRUM é a mais condizente com a realidade do negócio e tem apoio de pesquisas acadêmicas como a da  Universidade Federal de Itajubá, realizada com uma empresa de tecnologia de pequeno porte, em que se concluiu que a aplicação deste framework apresentou: 

**"melhoria na comunicação e aumento da colaboração entre envolvidos; aumento da motivação da equipe de desenvolvimento; diminuição no tempo gasto para terminar o projeto (prazo); diminuição do risco do projeto (menor possibilidade de insucesso).*

*Outros dois benefícios presentes na literatura foram medidos e notados pelos dados quantitativos do projeto piloto e de outros projetos da empresa: diminuição dos custos de produção (mão de obra) e aumento de produtividade da equipe."*

## Relação de Ambientes de Trabalho

| **Ambiente**                     | **Plataforma**                   | **Link de Acesso** |
|-----------------------------------|----------------------------------|--------------------|
| **Repositório de Código Fonte**   | GitHub            | [Código Fonte](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2025-1-e1-proj-web-t3-imobiflow/blob/main/src/README.md) |
| **Documentos do Projeto**         | GitHub             | [Documentos do Projeto](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2025-1-e1-proj-web-t3-imobiflow/tree/main/docs) |
| **Projeto de Interface**          | Mockflow             | [Projeto de Interface](https://mockflow.com) |
| **Gerenciamento do Projeto**      | GitHub                 | [Gerenciamento do Projeto](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2025-1-e1-proj-web-t3-imobiflow/projects) |


## Controle de Versão

A ferramenta de controle de versão adotada no projeto foi o
[Git](https://git-scm.com/), sendo que o [Github](https://github.com)
foi utilizado para hospedagem do repositório.

O projeto segue a seguinte convenção para o nome de branches:

- `main`: contém apenas código estável e revisado
- `dev`: usada para testar novas funcionalidades antes de serem integradas à main.
- `feature`: Para cada nova funcionalidade ou correção, cria-se uma branch a partir da dev (feature/nome-da-feature ou fix/nome-do-bug).

### Estrutura de branches

📂 main │ └── 📂 dev ├── 📂 feature/sistema-login ├── 📂 feature/melhoria-ui ├── 📂 feature/ajuste-navbar └── ...

Quanto à gerência de issues, o projeto adota a seguinte convenção para
etiquetas:

- `documentação 📖`: relacionadas à criação ou atualização da documentação do projeto.
- `desenvolvimento 💻`: tarefas e melhorias no código relacionadas à implementação de novas funcionalidades.
- `bug 🐛`: relatórios de erros ou falhas no sistema que precisam ser corrigidos.
- `infraestrutura 🏗️`: questões ligadas à configuração do ambiente, otimização ou hospedagem.
- `teste ✅`:testes de funcionalidades, correção de erros ou criação de novos cenários de teste.

### **Configuração do Projeto no Versionamento**  

O projeto foi configurado utilizando **Git** como sistema de controle de versão, com repositório hospedado no **GitHub**. A estrutura de branches, tags, commits, merges e issues foi definida para garantir um fluxo de trabalho organizado e eficiente.  

### **Gerência de Branches**  
A estrutura de branches foi simplificada para facilitar o desenvolvimento e a colaboração:  

- **`main`** – Branch principal, contendo a versão estável do projeto. Apenas código testado e aprovado é mesclado aqui.  
- **`dev`** – Branch de desenvolvimento, onde novas funcionalidades são integradas e testadas antes de irem para `main`.  
- **`feature/nome-da-feature`** – Branches criadas para cada nova funcionalidade. Sempre derivadas de `dev` e mescladas de volta após a conclusão do desenvolvimento.  

### **Gerência de Commits e Merges**  
- Commits seguem boas práticas, utilizando mensagens descritivas e padronizadas para facilitar o rastreamento das alterações.  
- As branches de `feature` são mescladas em `dev` por meio de **Pull Requests (PRs)**, garantindo revisão de código antes da integração.  
- A `dev` é mesclada na `main` apenas quando a versão estável do projeto está pronta para lançamento.  


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

Para a gestão das tarefas do projeto, estamos utilizando o GitHub com uma estrutura clara de fluxo de trabalho, dividida nas seguintes etapas:

| **Etapa**              | **Descrição**                                                                 |
|------------------------|-------------------------------------------------------------------------------|
| **Fila de Trabalho (Backlog)**  | É o Backlog do Produto e lista todas as características, funções, requisitos, melhorias e correções que formam as mudanças que devem ser feitas no produto nas futuras versões. |
| **Em Desenvolvimento**  | Lista as tarefas iniciadas e ainda não concluídas para testes |
| **Em Testes**           | Lista as tarefas aguardando a conclusão dos testes. |
| **Concluído**           | Lista os incrementos prontos,na condição utilizável e dentro das especificações de qualidade para entrega. |

Essas etapas ajudam a controlar o progresso das tarefas, garantindo que o fluxo de desenvolvimento seja organizado e transparente para todos os membros da equipe.  

O quadro kanban do grupo no GitHub está disponível no link https://github.com/orgs/ICEI-PUC-Minas-PMV-ADS/projects/1866/ e é apresentado, no estado atual, na figura abaixo:
 
 ![Quadro Kanban](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2025-1-e1-proj-web-t3-imobiflow/blob/main/docs/img/Captura%20de%20tela%20de%202025-03-21%2019-54-19.png?raw=true)


> **Links Úteis**:
> - [Planejamento e Gestáo Ágil de Projetos](https://pucminas.instructure.com/courses/87878/pages/unidade-2-tema-2-utilizacao-de-ferramentas-para-controle-de-versoes-de-software)
> - [Sobre quadros de projeto](https://docs.github.com/pt/issues/organizing-your-work-with-project-boards/managing-project-boards/about-project-boards)
> - [Project management, made simple](https://github.com/features/project-management/)
> - [Sobre quadros de projeto](https://docs.github.com/pt/github/managing-your-work-on-github/about-project-boards)
> - [Como criar Backlogs no Github](https://www.youtube.com/watch?v=RXEy6CFu9Hk)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

### Ferramentas

### **Ferramentas Utilizadas no Desenvolvimento**  

Durante o desenvolvimento do projeto, diversas ferramentas foram empregadas para facilitar a colaboração, organização e implementação do sistema.  

## **1. Comunicação**  
- **Microsoft Teams** – Utilizado para reuniões, alinhamentos e compartilhamento de arquivos da equipe. Escolhido por sua integração com outras ferramentas de produtividade e suporte a videoconferências.  
- **WhatsApp** – Utilizado para comunicações rápidas e informais, facilitando a troca ágil de informações entre os membros da equipe.  

## **2. Controle de Versão e Hospedagem**  
- **Git** – Sistema de controle de versão distribuído, essencial para gerenciar o histórico de mudanças e permitir colaboração eficiente no código.  
- **GitHub** – Plataforma utilizada para hospedagem do repositório, gerenciamento de branches, pull requests e issues, facilitando a organização e rastreabilidade do desenvolvimento.  

## **3. Desenvolvimento**  
- **Visual Studio Code** – Editor de código escolhido por sua leveza, suporte a extensões e integração nativa com Git, facilitando o desenvolvimento e depuração do projeto.  

## **4. Wireframing e Design**  
- **Mockflow** – Ferramenta utilizada para criar protótipos e wireframes das telas do sistema antes da implementação, garantindo um planejamento visual claro e reduzindo retrabalho no desenvolvimento.  

Cada ferramenta foi escolhida estrategicamente para otimizar a produtividade e comunicação da equipe, garantindo um fluxo de trabalho eficiente e bem estruturado.  
 
 