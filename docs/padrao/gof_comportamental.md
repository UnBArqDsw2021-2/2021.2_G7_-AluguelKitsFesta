# Histórico de Versão

| Data       | Versão | Descrição                  | Autor(es)        |
| ---------- | ------ | -------------------------- | ---------------- |
| 07/03/2022 | 1.0    | Criação do documento  | Victor |
| 14/03/2022 | 2.0    | Adicionando exemplo | Victor |



# GOFs Comportamentais

Os GoFs comportamentais são padrões de projetos mais voltados para alterações no nível do comportamento dos objetos.
Eles auxiliam principalmente quando são utilizados vários algoritmos diferentes.



## Strategy

O Strategy é um dos principais Gofs Comportamentais, que permite de maneira simples, variar dos algoritmos utilizados e resolver um certo problema.

O Strategy propõe uma solução que possibilita a variação facilitada do algoritmo a ser utilizado.
Um exemplo seria utilizar um função em python que é passada como parâmetro para um outro método.

O padrão de projeto strategy sugere que todos os algoritmos centralizados nesta classe sejam separados em outras classes.

### Quando usar?

É indicado usar, quando é necessário vários algoritmos com diferentes variações.
Além disso, quando existem declarações condicionais em torno de vários algoritmos relacionados. E por fim, quando muitas 'Classes' tem comportamento relacionado.

Exemplo do diagrama UML deste padrão, que pode ser aplicado no projeto:

![Aplicação Strategy](../padrao//imagens/strategy.png)

Exemplo de implementação em Python, que pode ser aplicado no projeto:

```python

from Calculator_de_impostos(object):
    def realiza_calculo(self, orcamento, imposto):

        imposto_calculado = imposto.calcula(orcamento)

        printf imposto_calculado

if __name__ == '__main__':
   
   from orcamento import Orcamento

   calculator = Calculator_de_impostos()

   orcamento = Orcamento(350)

   calculator.realiza_calculo(orcamento, ISS().calcula)
   calculator.realiza_calculo(orcamento, IOMS().calcula)

```
```python
class ISS(object):

    def calcula(self, orcamento):

        return orcamento.valor = 0.1

class ICMS(object):

    def calcula(self, orcamento):

        return orcamento.valor = 0.065

```
<center> 
Exemplo 1: Strategy implementada em python, aplicada no projeto.
</center>

Vantagens:

- Reutilização de código
- Manutenibilidade do código;
- É fácil alternar entre diferentes algoritmos (estratégias) em tempo de execução.
- Código limpo, pois se evita o código com excesso de estruturas condicionais.

Desvantagens:

- Aumento do número de classes do projeto.
- Aumento do número de objetos.

### Referências
> SERRANO, Milene. Arquitetura e Desenho de Software: Aula GoFs Comportamentais, disponível em: aprender3.unb 

> DevMedia. Estudo e Aplicação do Padrão de Projeto Strategy Disponível em: https://www.devmedia.com.br/estudo-e-aplicacao-do-padrao-de-projeto-strategy/25856.

> DevMedia. Design Patterns: Padrões “GoF” Disponível em https://www.devmedia.com.br/design-patterns-padroes-gof/16781

