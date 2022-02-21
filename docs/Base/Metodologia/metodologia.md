## Histórico de Versão

|    Data    | Versão |           Descrição           |    Autor     |
| :--------: | :----: | :---------------------------: | :----------: |
| 02/02/2022 |  1.0   |       Criação da página       | Victor Rayan |
| 03/02/2022 |  1.1   |    Adicionando Metodologia    | Victor Rayan |
| 04/02/2022 |  1.2   |   Adicionando Ferramerntas    | Victor Rayan |
| 09/02/2022 |  1.3   | Atualização/revisão dos dados | Luis Marques |
| 21/02/2022 |  1.4   | Revisão | Jaime Juan |

# Metodologias
## 1. Objetivo

<p align="justify">O objetivo principal deste documento é definir as metodologias e abordagens que serão utilizadas durante o desenvolvimento do projeto. </p>

## 2. Introdução

<p align="justify"> Pela dificuldade de se seguir as metodologias ágeis ao pé da letra, por obstáculos como tempo da disciplina de Arquitetura e Desenho de Software e desencontro de horários por parte dos membros da equipe. O grupo optou utilizar uma metodologia modificada que atendesse as necessidades da equipe. </p>

#### SCRUM

<p align="justify"> Scrum é uma metodologia ágil utilizada no desenvolvimento de Software baseado em processos iterativos e incrementais. Para isso, utiliza-se de  um  conjunto de práticas e papéis bem definidos que devem ser envolvidos durante o processo de desenvolvimento de software. 
 </p>

<p align="justify"> O Scrum é feito em Sprints, um pequeno ciclo iterativo, de 2 a 4 semanas, que fornece um resultado completo, uma variação do produto final. 
A equipe Scrum é formada por:
* Scrum master: a pessoa que lidera a equipe orientando-os a cumprir as regras e processos da metodologia.
* Product owner (PO): a pessoa responsável pelo notório saber e atribuições do produto.
* E a equipe com conhecimento técnico necessário que desenvolve o projeto em conjunto, desenvolvedores. </p>

<p align="justify"> Dessa forma, para o projeto a equipe utilizará os seguintes elementos do Scrum:  </p>

| Pipelines       | Descrição                                                       |
| --------------- | --------------------------------------------------------------- |
| Sprints         | Pequeno ciclo iterativo de 1 semana*                             |
| Sprint Planning | Evento que abre um novo ciclo de execução                       |
| Sprint Review   | Revisão da situação do projeto no final de cada Sprint          |
| Product Backlog | Lista de atividades que precisam ser feitas durante uma Sprint. |
| Planning poker  | Estratégia que busca uma estimativa via consenso da equipe.     |

<p align="justify"> Assim sendo, utilizaremos modelo tradicional com pequenas alterações, como a utilização de Sprints de 1 semana.  </p>

#### Extreme Programming XP

<p align="justify"> XP também é uma metodologia ágil, que também visa entregas frequentes em pequenos espaços de tempo para melhorar a qualidade do software e a capacidade de resposta às mudanças nos requisitos do cliente. O Extreme Programming possui como um dos principais elementos o Code Review e o Pair Programming, técnica ágil onde dois programadores trabalham juntos, onde um escreve enquanto o outro observa e revisa. Sendo assim, do XP será adotado no projeto a utilização de tais técnicas. </p>

#### Kanban

<p align="justify"> Com origem na área automotiva, o Kanban é uma metodologia  visual de gestão de trabalho. É bastante útil para se fazer uma boa gestão de projetos. Por isso, a equipe decidiu utilizar esse sistema, através da ferramenta Zen-Hub. Nessa ferramenta utilizaremos de 5 colunas ou pipelines:</p>

| Elementos     | Descrição                             |
| ------------- | ------------------------------------- |
| Backlog       | Tarefas a fazer                       |
| SprintBacklog | Tarefa a se realizar na sprint atual  |
| Doing         | Tarefas em andamento                  |
| Review        | Tarefas que estão a espera de revisão |
| Done          | Tarefas terminadas                    |

#### Processo de Desenvolvimento

<p align="justify"> Contudo, o processo de desenvolvimento e mensuração em resumo decidido pela equipe é apresentando nos seguintes tópicos:</p>

<ul align="justify">
    <li>O projeto será elaborado utilizando metodologias ágeis. Utilizaremos parte do Scrum modificado com Xp.</li>
    <li>Foi atribuido para o integrante <a href="https://github.com/JaimeJuan11" target="_blank">Jaime</a> a função de Scrum Master .</li>
    <li>Foi atribuído para o Integrando <a href="https://github.com/luisgfmarques" target="_blank">Luis Marques</a> O papel de Product Owner.</li>
    <li>Foi atribuído para o Integrando <a href="https://github.com/CaioGabrielAraujo" target="_blank">Caio Gabriel</a> O papel de DevOps.</li>
    <li> Todos os membros do projeto serão desenvolvedores.</li>
    <li>Será feito Sprints mais curtas, com duração de uma semana, por conta do tempo curto para desenvolvimento do projeto.</li>
    <li>Ao final de cada ciclo será realizado as “Sprints Reviews”, será averiguado o quadro Kanban e atualizaremos o BackLog conforme as necessidades da equipe.</li>
    <li>Nas Sprints Reviews utilizaremos o Planning Poker para consenso da equipe quanto às estimativas (tempo e esforço) dos itens do Product Backlog.</li>
    <li>Será utilizado o “Pair Programming” onde será feito o pareamento em duplas para troca de conhecimentos e desenvolvimento conjunto do projeto.</li>
    
</ul>

## Ferramentas

<p align="justify"> As ferramentas utilizadas pela equipe até o presente momento são:</p>

<table>
    <tr>
        <th>Ferramenta</th>
        <th>Nome</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>
            <img src="../telegram.png" alt="drawing" style="width: 100px;border-radius: 50%;"/>
        </td>
        <td style="padding-top: 50px;">
            Telegram
        </td>
        <td style="padding-top: 50px;">
            <a  target="_blank">O Telegram será utilizado para troca de mensagens rápidas e comunicação geral da equipe.</a>
        </td>
    </tr>
        <tr>
        <td>
            <img src="../teams.jpeg" alt="drawing" style="width: 100px;border-radius: 50%;"/>
        </td>
        <td style="padding-top: 50px;">
            Teams
        </td>
        <td style="padding-top: 50px;">
            <a  target="_blank">Será utilizado para reuniões, gravação de video, além de armazenar arquivos úteis da equipe</a>
        </td>
    </tr>
    <tr>
        <td>
            <img src="../zenhub.png" alt="drawing" style="width: 100px;border-radius: 50%;"/>
        </td>
        <td style="padding-top: 50px;">
            Zenhub
        </td>
        <td style="padding-top: 50px;">
            <a  target="_blank">Utilizaremos para executar a metodologia Kanban</a>
        </td>
    </tr>
        <tr>
        <td>
            <img src="../drive.png" alt="drawing" style="width: 100px;border-radius: 50%;"/>
        </td>
        <td style="padding-top: 50px;">
            Drive
        </td>
        <td style="padding-top: 50px;">
            <a  target="_blank">Compartilhar documentos entre a equipe</a>
        </td>
    </tr>
     <tr>
        <td>
            <img src="../figma.png" alt="drawing" style="width: 100px;border-radius: 50%;"/>
        </td>
        <td style="padding-top: 50px;">
            Figma
        </td>
        <td style="padding-top: 50px;">
            <a  target="_blank">Utilizaremos para prototipagem de projetos de design baseado principalmente no navegador web</a>
        </td>
    </tr>
    <tr>
        <td>
            <img src="../github.png" alt="drawing" style="width: 100px;border-radius: 50%;"/>
        </td>
        <td style="padding-top: 50px;">
           Github
        </td>
        <td style="padding-top: 50px;">
            <a target="_blank">
            Será utilizado como plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git.</a>
        </td>
    </tr>
</table>

## Referências Bibliográficas

> O que é um Scrum Master e qual o seu papel?. Disponível em: https://www.ieepeducacao.com.br/Scrum. Acesso em: 2 de fevereiro de 2022.

> Kanban: Conceito, como funciona, vantagens e implementação. Disponível em: https://www.totvs.com/blog/negocios/kanban/. Acesso em: 2 de fevereiro de 2022.