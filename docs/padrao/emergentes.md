## Histórico de Versão

| Data       | Versão | Descrição                                                 | Autor(es)      |
| ---------- | ------ | --------------------------------------------------------- | ------------ |
| 10/03/2022 | 1.0    | Criação do documento                                      | Marcos Gabriel Tavares|


# Padrões de projeto emergentes
## Introdução
Padrões de projeto, tambem conhecidos como design patterns, são soluções generalistas para problemas recorrentes durante um desenvolvimento de um software, é uma definição alto nivel de como o problema pode ser solucionado. Alguns padrões emergentes que pretendemos utilizar no desenvolvimento do PartyRent são:

 - MVC

## MVC
O MVC tem como principal objetivo: separar dados ou lógicos de negócios (Model) da interface do usuário (View) e o fluxo da aplicação (Controller), a idéia é permitir que uma mensagem da lógica de negócios possa ser acessada e visualizada através de várias interfaces. Na arquitetura MVC, á lógica de negócios, ou seja, nosso Model não sabe quantas nem quais as interfaces com o usuário esta exibindo seu estado, a view não se importa de onde esta recebendo os dados, mas ela tem que garantir que sua aparência reflita o estado do modelo, ou seja, sempre que os estados do modelo mudam, o modelo notifica as view para que as mesmas atualizem-se.  
  

![MVC](https://arquivo.devmedia.com.br/REVISTAS/easyjava/imagens/9/3/image001.jpg)


## Referências
-   Design Patterns – O que são e quais os benefícios?:  [https://www.opus-software.com.br/design-patterns/](https://www.opus-software.com.br/design-patterns/). Último acesso em 10/03/2022.

- Abordando a arquitetura MVC, e Design Patterns: Observer, Composite, Strategy: [http://www.linhadecodigo.com.br/artigo/2367/abordando-a-arquitetura-mvc-e-design-patterns-observer-composite-strategy.aspx](http://www.linhadecodigo.com.br/artigo/2367/abordando-a-arquitetura-mvc-e-design-patterns-observer-composite-strategy.aspx). Último acesso em 10/03/2022.
