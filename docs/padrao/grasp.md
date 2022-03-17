## Histórico de Versão

| Data       | Versão | Descrição                         | Autor(es)    |
| ---------- | ------ | --------------------------------- | ------------ |
| 07/03/2022 | 1.0    | Criação do Documento              | Jaime Juan e Flavio |

# GRASP(s)

## 1. Introdução

GRASP, sigla para General Responsability Assignment Software Patterns, são padrões que consistem em um conjunto de práticas para a atribuição de responsabilidades a classes e objetos em projetos orientados a objeto.

Assim sendo, temos os seguintes padrões utilizados:
1. Controlador (Controller)
2. Criador (Creator)
3. Indireção (Indirection)
4. Especialista na informação (Information expert)
5. Alta coesão (High cohesion)
6. Baixo acoplamento (Loose coupling)
7. Polimorfismo (Polymorphism)
8. Variações protegidas (Protected variations), e
9. Invenção pura (Pure fabrication)

Esses padrões servem para a resolução de problemas comuns e bastante típicos de desenvolvimento de software orientado a objeto. Com isso, o uso de tais técnicas apenas documentam e normatizam as práticas já consolidadas, testadas e conhecidas no mercado.

## 2. Padrões
### 2.1. Controlador (Controller)
O padrão Controller atribui a responsabilidade de manipular eventos do sistema para classes que não são da interface do usuário (UI) que representam cenários globais ou de casos de uso. Objetos de controlador são objetos de interface não-usuário responsáveis ​​por receber ou manipular eventos do sistema.

Um caso de uso de controlador deve ser usado para lidar com todos os eventos de caso de uso e pode ser usado para vários casos de uso (por exemplo, para casos de uso como criar usuário e excluir usuário, ele pode ter um controlador de usuário em vez de dois casos de uso de controlador separados ).

Ele é definido como o primeiro objeto fora da camada de interface do usuário que recebe e coordena as operações do sistema ("controles"). O controlador deve delegar o trabalho que precisa ser feito a outros objetos; ele coordena ou controla a atividade. Ele não pode fazer muito trabalho sozinho. O controlador GRASP pode ser pensado como parte da camada de aplicação/serviço [2] (assumindo que a aplicação tem uma distinção clara entre a camada de aplicação/serviço e a camada de domínio em um sistema orientado a objetos, com uma camada comum na lógica arquitetura) sistema de informação).

### 2.2. Criador (Creator)



### 2.3. Indireção (Indirection)



### 2.4. Especialista na informação (Information expert)



### 2.5. Alta coesão (High cohesion)



### 2.6. Baixo acoplamento (Loose coupling)



### 2.7. Polimorfismo (Polymorphism)



### 2.8. Variações protegidas (Protected variations)



### 2.9. Invenção pura (Pure fabrication)
## Referências

> 