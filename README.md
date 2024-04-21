Tutorial introdutório sobre Git e Github
========================================

Este repositório contém instruções para um tutorial de uso do Git e Github
com foco nos comandos introdutórios para a criação de um _pull request_.


Preparação para a execução do exercício
---------------------------------------

Para iniciar este exercício, faça um _fork_ do repositório
[https://github.com/exercicios-programacao/github-pr-tutorial](https://github.com/exercicios-programacao/github-pr-tutorial)
para o seu usuário do Github.

Siga as orientações para a preparação do ambiente de desenvolvimento 
contidas nesse documento.

Todo o código implementado deve estar dentro do diretório `src`. Siga as 
instruções contidas no arquivo [`INSTRUCOES.md`](INSTRUCOES.md), que contém
os objetivos e etapas para a realização do exercício.


Instalação das Dependências
---------------------------

Para realizar este exercício você deverá utilizar a linguagem de programação
Python, na versão 3.11 ou superior.

Para isolar o ambiente de desenvolvimento, é sugerido o uso de ambientes 
virtuais do Pyhton, que você pode criar com os comandos:

```
$ python -m venv .venv
```

Em cada seção de desenvolvimento você deve iniciar e atualizar o ambiente
de desnevolvimento.

Para inicializar o ambiente virtual no Linux ou macOS, utilize:

```
$ . .venv/bin/activate
````

Para iniciar o ambiente virtual no Windows, utilize:

```
PS > .venv/bin/activate.bat
```

Em cada seção de desenvolvimento você deve atualizar o ambiente de
desenvolvimento, com as dependências necessárias para o desenvolvimento
do projeto:

```
pip install -e .
```

Se você quiser utilizar o `tox` para executar os testes, você deve instalar
o ambiente com a opção `tox`:

```
pip install -e .[tox]
```


Desenvolvimento
---------------

Durante o desenvolvimento do exercício, você pode executar os testes,
localmente, utilizando os comandos `tox` ou `behave`. A diferença entre os 
dois é que o `behave` executa apenas os testes funcionais e o `tox` executa 
os testes de qualidade de código, como formatação e boas práticas.

É sugerido que se trabalhe em um cenário de cada vez, o que pode ser obtido 
utilizando-se o comando `behave --stop`, para que os testes funcionais 
parem na primeira falha.


Conclusão do Exercício
----------------------

O exercício é concludio quando é criado um _pull request_ contra o
[repositório original](https://github.com/exercicios-programacao/github-pr-tutorial). Para isso, será
necessário que a solução para o problema seja encontrada e que exista, ao
menos, um novo _commit_ no código, e que o _fork_ criado seja atualizado.

O _pull request_ deve conter um título, e, opcionalmente, um comentário.

