## Problemas-de-producao-resolvidos-em-python

Neste repositório, estão alguns problemas de produção, junto a suas resoluções modelados e resolvidos em python. 

## Pacotes utilizados

São utilizados dois pacotes Python para interface com o CPLEX Optimizer:

- [cplex](https://pypi.org/project/cplex/): biblioteca de baixo nível que faz a conexão com a implementação em C do CPLEX, poderosa porém relativamente complexa.
- [DOcplex](https://www.ibm.com/docs/en/icos/22.1.1?topic=api-docplex-examples): interface orientada a objetos para o CPLEX, menos poderosa, mas bem mais simples de usar.

Elas não vêm instaladas por padrão no [Anaconda](https://www.anaconda.com/), mas podem ser facilmente instaladas abrindo o console Python e executando o comando:

```sh
>>> pip install cplex docplex
```
