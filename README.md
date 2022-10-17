# HealthStock 👩‍⚕️🚚🤵

Uma aplicação com o intuido de criar um ambiente de comprar e venda de produtos hospitalares.

# Integrantes
- Leonardo Ruiz Bottura - RA: 820130421
- Denis Ribeiro Leme - RA: 822225770
- Bruno Serafim de Araujo - RA: 821150834
- Gabriel Santana Quirino Silva - RA: 821127846
- Gustavo Henrique Ribeiro Meneses - RA: 821135489
- João Gabriel de Oliveira Santos Conceição - RA: 821135788

# Arquitetura 🏗️

O sistema é dividido em microsserviços com propositos diferentes, cada um com uma importante funcionalidade.

## Serviço de Login

O sistema de autenticação é feito por esse serviço, de forma descentralizada.

[Click aqui para o repositório do serviço de login](https://github.com/JoaoGabrielOliveira/healthstock-login).


## Serviço de Produtos

O sistema para gerenciamento dos produtos ofertados para nossa aplicação. Dentre suas principais funções é o cadastro de produtos e retorno dos produtos cadastrados

[Click aqui para o repositório do serviço de produtos](https://github.com/JoaoGabrielOliveira/healthstock-products).

## Serviço de Pedidos

# Utils

### Lista de todos os endpoints dos serviços para POSTMAN

1. Baixe esse repositório
2. Baixe e instale o software **Postman**
3. Localize o botão " *import* " ou "Importar" no **Postman**
3. Selecione o arquivo ' *postman_collection.json* '
4. _Coloque para rodar_ a aplicação que deseja testar


### Para atualizar todos os submodules

```shell
git submodule update --remote
```
