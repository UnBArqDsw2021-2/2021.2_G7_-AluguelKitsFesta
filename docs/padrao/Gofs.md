## Gof Estrutural
---

## Versionamento
| Data | Versão | Descrição | Autores |
| -------- | -------- | -------- | ---|
| 07/03/2022     |  1.0  | Criação do documento  | Mateus Brandão Teixeira

Os padrões estruturais se preocupam com a forma como classes e objetos são compostos para formar estruturas maiores. Os de classes utilizam a herança para compor interfaces ou implementações, e os de objeto ao invés de compor interfaces ou implementações, eles descrevem maneiras de compor objetos para obter novas funcionalidades. A flexibilidade obtida pela composição de objetos provém da capacidade de mudar a composição em tempo de execução o que não é possível com a composição estática (herança de classes).

# Adapter 
O Adapter é um padrão bem simples de compreender,sendo sua principal funcionalidade converter a interface de uma classe para outra interface que o cliente já espera receber.Trazendo para o mundo real podemos usar um exemplo que ocorreu na construção civil quando o governo padronizou o uso de tomadas,com isso as contruções eram entregues com esse novo padrão,porém muitos de nossos aparelhos, fabricados antes da definição do novo padrão, não eram mais compatíveis com essas tomadas.Com isso,foi necessário o uso de adaptadores para permitir a utilização de aparelhos antigos nas tomadas com o novo padrão.Entrando no mundo computacional O padrão de adaptador geralmente é usado quando precisamos instalar uma nova biblioteca de classes adquirida de um fornecedor em um sistema de software existente, mas essas novas bibliotecas de classes de fornecedores não são as mesmas que as bibliotecas de classes antigas de fornecedores. Como não temos o código do novo fornecedor e não podemos alterá-lo, podemos criar uma classe para fazer essa adaptação, que é responsável por adaptar a interface do novo fornecedor ao que o sistema espera. Adaptadores são amplamente utilizados para tornar seu sistema compatível com outros frameworks ou APIs.

# É possível adaptar a nossa forma de organização de projeto com este padrão?
Sim no futuro existe grande possibilidade de termos que utilizar esse padrão,pois os softwares sempre estão em constate evolução.Isso se deve a necessidade de sempre ajustar e melhorar o produto.Portanto é bem provável que em realeses para melhorias seja necessário utilizar o adapter.

