# Xeque-mate

## Manifesto

> Enredo: A Matrix está selecionando em seu sistema quais humanos serão eliminados conforme uma rotina denominado **xeque_mate**. *Morpheus e seus aliados* tem como missão interceptar a lista de *red_pills* e impedir que o expurgo seja executado pelos *agentes*.

### Desafio

*Resumo*: Com base neste pequeno enredo, desenvolva um programa contendo uma lista e um algorítmo de seleção para identicar 7 nomes na lista e removê-los.

1. Criar um objeto lista com o nome *red_pills* de tamanho 10 contendo os seguintes elementos: [nome, data de nascimento, sexo].

2. Desenvolva uma função para retornar 7 nomes aleatórios da lista red_pills.

3. Criar função para identificar os nomes selecionados e removê-los da lista red_pills.

4. Criar variável *xeque_mate* do tipo booleano, para notificar que ação de limpeza foi executada.

5. A execução do programa deve partir de um módulo de testes de unidade para as seguintes validações:

    - Validar número total de elementos selecionados na lista subtraindo com o size da lista original

    - Validar quais nomes foram selecionados na lista

    - Validar a exclusão de nomes da lista

    - Verificar se xeque_mate é True

## Regras

- Construir projeto utilizando o compilador python 3.11.2
- Virtualizar projeto com a ferramenta **venv**
  >A execução deste passo é essencial para o projeto.
  
- Adotar biblioteca pytest para execução dos testes
- O projeto deve contemplar uma estrutura de testes usando *Test Driven Development (TDD)*
- Gerar arquivo *requirements.txt* para instalação das bibliotecas conforme a sessão [Tecnologias](Tecnologias)
- Disponibilizar projeto no *github*

## Tecnologias

- python 3.11.2
- pytest
- pylint
- autopep8
