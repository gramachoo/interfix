

 # INTERFIX 🤖
 
### Quem somos?
A InterFix é uma empresa dedicada a transformar o suporte técnico empresarial por meio do uso de inteligência artificial. Nosso objetivo é conectar soluções inteligentes com as necessidades de nossos clientes, oferecendo assistência eficiente, personalizada e em tempo real.

<p><img width="700 height="500" alt="Logo Empresa" src="https://github.com/user-attachments/assets/8aa8a096-88fa-4be4-952c-946d63ceed66">

</p>

 
   
   | <a href=#desafio>Desafio</a> | <a href=#backlog>Backlog do Produto</a> |
   <a href=#sprint>Cronograma de Sprints</a> | <a href=#tecnologias>Tecnologias Utilizadas</a> | <a href=#estrutura>Estrutura do Projeto</a> | <a href=#execucao>Execução do Projeto</a> | <a href=#documentacao>Documentação</a> | <a href=#equipe>Integrantes</a> | <a href=#dor>DoR</a> | <a href=#dod>DoD</a> |
   
   > Status do Projeto: Em andamento ⏳
>

  



> ## Desafio <a id="desafio"></a> 🏅

O desafio consiste em criar uma aplicação web, desktop e mobile de suporte tecnico e gestão de chamados com integração de IA. O aplicativo possuira três níveis de acesso e deve ser capaz de analisar e atribuir a prioridade do chamado, também atribuirá o chamado ao técnico que tiver a carga horária mais baixa. Além da criação e gestão de chamadas, o sistema deverá gerar e gerenciar relatórios (com filtro de tempo), disponibilizando também uma função para gerenciar os níveis de acesso (função à qual somente o administrador poderá acessar).

> ## Solução 🏅
InterFix ST. Permitirá aos usuários criar ou gerenciar chamadas dependendo do seu nível de acesso, que é dividido em 3 (Administrador, Técnico e Funcionário). As chamadas têm níveis de prioridade que são distribuídos em Baixo, Médio, Alto e Crítico. Critérios como a prioridade das chamadas serão decididos pela IA durante a atribuição da prioridade, que depois perguntará ao usuário se concorda com o nível de prioridade da chamada. Uma vez que uma chamada é atribuída a um técnico e resolvida, o sistema criará um relatório que será guardado por 2 anos junto com a chamada.

> ## Backlog do Produto<a id ="backlog"></a> 🔩
O backlog do produto esta [aqui](https://github.com/gramachoo/interfix/blob/main/Backlog/BackLog%20do%20Produto.md)


> ## Cronograma de Sprints <a id="sprint"></a> 📅
  
| Sprint          |    Período    | Documentação                            |
| --------------- | :-----------: | ----------------------------------------|
| 🔖 **SPRINT 1** | 18/08 - 25/08 | [Sprint1](https://github.com/gramachoo/interfix/blob/main/Scrum/Relatorios%20Sprints/Sprint1.md) |
| 🔖 **SPRINT 2** | 01/09 - 08/09 | [Sprint 2](https://github.com/gramachoo/interfix/blob/main/Scrum/Relatorios%20Sprints/Sprint2.md) |
| 🔖 **SPRINT 3**| 08/09 - 15/09 |[Sprint 3](https://github.com/gramachoo/interfix/blob/main/Scrum/Relatorios%20Sprints/Sprint3.md) |
| 🔖 **SPRINT 4**| 15/09 - 22/09 |[Sprint 4](https://github.com/gramachoo/interfix/blob/main/Scrum/Relatorios%20Sprints/Sprint4.md) |
| 🔖 **SPRINT 5**| 22/09 - 29/09 |[Sprint 5](https://github.com/gramachoo/interfix/blob/main/Scrum/Relatorios%20Sprints/Sprint5.md)|
| 🔖 **SPRINT 6**| 29/09 - 06/10 |[Sprint 6](https://github.com/gramachoo/interfix/blob/main/Scrum/Relatorios%20Sprints/Sprint6.md)|
| 🔖 **SPRINT 7**| 06/10 - 13/10 |[Sprint 7](https://github.com/gramachoo/interfix/blob/main/Scrum/Relatorios%20Sprints/Sprint7.md)|


> ## Tecnologias Utilizadas <a id="tecnologias"></a> 💻 

Categoría | Tecnologías
--------- | -------------
FrontEnd | HTML, CSS e Figma (Modelagem da interface) 
BackEnd |  C#
Base De Dados | BrModel e SQL Server (Windows Server)
IA | BlackBox AI
Metodología | Scrum + Git FLow 

> ## Estrutura do projeto 🏗️ <a id="estrutura"></a>

A estrutura do projeto pode ser acessada [aqui](https://github.com/gramachoo/interfix/blob/main/Docs/Estrutura%20do%20projeto/Estrutra%20do%20Projeto.md)


> ## Execução do Projeto 🗃 <a id="execucao"></a>

O manual de instalaçao pode ser acessado [aqui](https://github.com/gramachoo/interfix/blob/main/Docs/Manual%20de%20Instalção/Manual%20de%20Instação.md)

> ## Documentação 📄<a id="documentacao"></a>

A documentação pode ser acessada [aqui](https://github.com/gramachoo/interfix/tree/main/Docs)

> ## Integrantes <a id="equipe"></a>👥

Função       | Nome                | Github                                                       |
------------ | --------------------| -------------------------------------------------------------|
Project Owner| Christian Fernandes | [Acessar Github](https://github.com/ChristianFernandesLemos) |
Scrum Master | Juan Vargas         | [Acessar Github](https://github.com/RenteriaJuan)            |
Dev Team     | Théo Pinto          | [Acessar Github](https://github.com/Thorphinm)               |
Dev Team     | Ana Beatriz         | [Acessar Github](https://github.com/Anasouza2802)            |
Dev Team     |Gustavo Gramacho     | [Acessar Github](https://github.com/gramachoo)               |
Dev Team     | Lukas Keiji         | [Acessar Github](https://github.com/Lucaskeiji)              |


> ## DoR - Definition of Ready <a id="dor"></a> 🏃

* User Stories com **Critérios de Aceitação**
* Design no **Figma**
* Modelagem do **Banco de Dados**
* Criação das Classes
* Modelo de iteração


> ## DoD - Definition of Done 🏆 <a id="dod"></a>

* [Manual da Aplicação](https://github.com/gramachoo/interfix/blob/main/Docs/Manual%20de%20Instalção/Manual%20de%20Instação.md)
* [Manual de Usuário](https://github.com/gramachoo/interfix/blob/main/Docs/Manual%20de%20usuario/Manual_de_Uso_InterFix.docx)

