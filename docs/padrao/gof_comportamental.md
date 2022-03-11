# Histórico de Versão

| Data       | Versão | Descrição                  | Autor(es)        |
| ---------- | ------ | -------------------------- | ---------------- |
| 07/03/2022 | 1.0    | Criação do documento  | Victor |



# GOFs Comportamentais

Os GoFs comportamentais são padrões de projetos mais voltados para alterações no nível do comportamento dos objetos.
Eles auxiliam principalmente quando são utilizado vários algoritmos diferentes.



## Strategy

O Strategy é um dos principais Gofs Comportamentais, que permite de maneira simples, variar dos algoritmos utilizados resolver um certo problema.

O Strategy propõe uma solução que possibilita a variação facilitada do algoritmo a ser utilizado.
Ou seja utiliza-se um função em python e é passada como param~etro para um outro metodo.

O padrão de projeto strategy sugere que todos os algoritmos centralizados nesta classe sejam separados em outras classes.

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

Vantagens:
- Reutilização de código
- Maior manutenibilidade do código;
- Maior dinamismo (possível mudar a estratégia em tempo de execução);
- Maior legibilidade do código.

Desvantagens:
- Aumento do número de classes do projeto.
- Aumento do número de objetos.

